# Health-Insurance-Cross-Sell-Prediction
An insurance company has provided Health Insurance to its customers and would like to predict whether the policyholders will be interested in the Vehicle Insurance provided by the company. The data provided include a train data and test data. There are around 3,80,000 entres in the train data and 1,27,000 entries in the test data. The train data has 12 features with information about demographics(Gender, Age, Region_code, Driving License), Vehicles(Vehicle Age, Vehicle Damage), Policy (Annual Premium, Policy Sales Channel, Vintage, Previously Insured), also the Response of the customers. The target variable here is the "Response" a binary variable with 0 & 1. Here, 1 means the customer is interested in the Vehicle insurance policy and 0 indicate the customer is not interested.

The models could be build by training the model on the train data, hence it is a Supervised Learning process. Since the response variable is a binary variable, Classification models are required for prediction. Logistic regression model, Decision Tree model, Random Forest Classifiers and XGBoost are the preferred Classification models. The best model out of the three is selected based on the accuracy score, confusion matrix and roc results.

Variables:

id - Unique ID for the customer

Gender - Gender of the customer

Age - Age of the customer

Driving_License - 0: Customer does not have DL, 1 : Customer already has DL

Region_Code - Unique code for the region of the customer

Previously_Insured - 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

Vehicle_Age - Age of the Vehicle

Vehicle_Damage - 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

Annual_Premium - The amount customer needs to pay as premium in the year

Policy_Sales_Channel - Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage - Number of Days, Customer has been associated with the company

Response - 1 : Customer is interested, 0 : Customer is not interested
