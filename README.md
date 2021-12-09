# Supply-Deman-and-price-prediction-with-Machine-leaning-regression-model-
With the help of import-export data collected by various organization Price is predicated by three machine learning algorithm's- Random Forest, SVR, Gradient boost algorithms.
This work is rework and some of the extended work done by the author of the paper title "Machine Learning-Based Regression Models for Price Prediction in the Australian Container Shipping Industry: Case Study of Asia-Oceania Trade Lane"
Link:https://doi.org/10.1007/978-3-030-44041-1_5.

![image](https://user-images.githubusercontent.com/46283676/145195987-7062750d-0337-4dc1-9438-27d643e29868.png)

Cargo volumes in Shipping Industry that are highly seasonal in contrast, supply or shipping capacity is fixed in the short term. This results in periods of mismatched supply and demand and therefore shipping price volatility. The current spot market pricing practice of using data validity and not vessel voyage. This causes a disconnect between price and supply and demand.


Prediction have been done by applying three different regression models over the gathered datasets which includes
Support Vector Regression (SVR)
Random Forest Regression (RFR) and 
Gradient Booster Regression (GBR)


Data Sourcing

We have selected Asia-Oceania trade lane data for the application.
The shipping capacity (supply) dataset is sourced from Sea-Intelligence.
The pricing data for the Asia Oceania trade lane is gathered from  Shanghai Freight Index (SCFI) and (2) Mizzen group propriety database.
The shipment demand dataset is collected by sourcing data from five international Australian ports. These ports include Port Botany, Port of Melbourne, Fremantle Port, Flinders Port and the Port of Brisbane.


Pre-processing of DATA

The total shipment demand for imports of ports of Asia-Oceania trade lane can be calculated by summing of full and empty containers for imports.

                                                            D (I) = CF (I) + CE (I)
                           
D (I) represents total import shipment demand for Asia-Oceania trade lane And, CF (I) and CE (I) represents a total of full and empty containers for imports in Asia Oceania trade lane. Once the weekly shipment demand is calculated for each port, they are summed up to get total shipment demand for the Asia Oceania trade lane.

![image](https://user-images.githubusercontent.com/46283676/145197038-87af389b-bb94-4d25-bc7b-23597afe3f35.png)

The data integration process involves combining supply, demand and price datasets into a single unified dataset. The final dataset used for predicting the weekly import container price, based on demand and supply.

![image](https://user-images.githubusercontent.com/46283676/145197236-d9627d67-8203-48fa-8c4a-b7e4a2eefe20.png)

![image](https://user-images.githubusercontent.com/46283676/145197268-816109f1-e72e-4bd1-89c5-da4fd2907959.png)


Result:

![image](https://user-images.githubusercontent.com/46283676/145197326-287cb2a0-62e6-4de7-8db3-42f3292724eb.png)

![image](https://user-images.githubusercontent.com/46283676/145197388-28d79e90-6238-4013-a8db-99d1696870a9.png)

Conclusion:

In this Project, with the help of three regression-based ML models we have predict the price of import shipment containers in the Australian shipping industry. The container price is predicted based on current demand and available supply. To analyze the performance of these models, R2 score, accuracy, and RMSE are measured. Our study shows that using the ML algorithm for predicting shipment prices can positively affect the shipping industry. Comparing accuracy we get the GBR model to be best in all case training, testing and validation also.
