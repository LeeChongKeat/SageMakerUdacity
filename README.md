# SageMakerUdacity
This project is Deep Project to predict the review is positive or negative and used the SageMaker to predict. It's required the Python, pytorch and AWS Sagemaker knowledge

## Create AWS SageMaker
1) Logging into AWS
2) Search SageMaker
3) Create Notebook Instance
3.1) Notebook instance settings - In this section, you may choose the notebook instance name of your choice. By default, a ml.t2.medium type is available. But, we will use ml.p2.xlarge for training a model and ml.m4.xlarge for deployment.
4) git clone https://github.com/udacity/sagemaker-deployment.git
5) Start Project

## Create AWS Lambda
1) Search Lambda
2) Create Function
3) Enter function name and select Runtime -> Pythion 3.6
4) Update the endpoint
5) Create


# #Create Lambda API Gateway
1) Search API Gateway
2) Create API
3) Select New API, API Name
5) Deploy API
4) Select Lambda Function
5) Name as prod

## Update Index.html
1) Update the API Gateway 

