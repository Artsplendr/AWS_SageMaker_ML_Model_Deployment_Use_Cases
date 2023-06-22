# AWS_SageMaker_ML_Model_Deployment_Use_Cases

## Case 1 "Deploy a Machine Learning Model to Real-Time Inference Endpoint"
#### Reference: AWS Tutorial is available at [the following link](https://aws.amazon.com/getting-started/hands-on/machine-learning-tutorial-deploy-model-to-real-time-inference-endpoint/?ref=gsrchandson)

In this example, we can learn how to deploy a ML model to real-time inference endpoint, by using Amazon SageMaker notebook instance.

**Model**: binary classification pre-trained XGBoost model.  

**Dataset**: synthetic auto insurance claims dataset. The dataset consists of details and extracted features from claims and customer tables along with a fraud column indicating whether a claim was fraudulent or not. The model predicts probability of a claim being fraudulent.

## Case 2 "Deploy a Multi-Model Endpoint to a Real-Time Inference"
#### Reference: AWS Tutorial is available at [this link](https://aws.amazon.com/getting-started/hands-on/deploy-multi-model-endpoint-realtime-inference/?ref=gsrchandson&id=new)

Based on the AWS tutorial, we learn how to deploy a multi-model endpoint with multiple trained machine learning models to a single real-time inference using an Amazon SageMaker notebook instance.

**Models**: set of binary classification XGBoost models that has already been pre-trained.  Each of these models predicts housing prices for a single location. 

**Dataset**: synthetic house price prediction dataset. 
The dataset has such features as number of bedrooms, square feet, and number of bathrooms.
