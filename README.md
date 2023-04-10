## Prediction of Cross-sell Opportunities for Insurance Policies

Original project on my Kaggle: [Health Insurance Project](https://www.kaggle.com/code/daniloortelli/health-insurance-project)

The customer is an insurance company that has provided health insurance to its customers.
The company would like to know how many customers would accept to purchase a vehicle insurance.

The dataset consists of the following properties:

- id: unique id of the buyer;
- Gender: gender of the buyer;
- Age: age of the buyer;
- Driving_License: 1 if the user has a driving license, 0 otherwise;
- Region_Code: unique code of the buyer's region;
- Previously_Insured: 1 if the user already has an insured vehicle, 0 otherwise;
- Vehicle_Age: age of the vehicle;
- Vehicle_Damage: 1 if the user has damaged the vehicle in the past, 0 otherwise;
- Annual_Premium: the amount that the user must pay as a premium during the year;
- Policy_Sales_Channel: anonymized code of the channel used for the proposal (e.g. by email, by phone, in person, etc ...);
- Vintage: number of days from which the user is a customer of the company;
- Response: 1 if the buyer has responded positively to the sales proposal, 0 otherwise.


The goal of this project is the following:

_Predict the value of Response providing the insurance company with a predictive model that can predict whether past year's policyholders might be interested in purchasing an insurance for their vehicle as well._
