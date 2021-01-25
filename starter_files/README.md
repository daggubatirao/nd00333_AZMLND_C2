# Operationalizing Machine Learning in Azure
## Overview
This project is part of the Udacity Azure ML Nanodegree. In this project, we build and operationalize an Azure ML pipeline using Azure Machine Learning Studio and Azure ML Notebooks using Python SDK. 

In Azure Machine Learning Studio, an AutoML run is confugred for the given dataset. The AutoML Run identifies the best model using a defined metric such as accuracy or AUC ..etc. The best model is then deployed to Azure Container Instances(ACI) or Azure Kubernetes Instances(AKI). The deployment creates an endpoint, which can be inspected using Swagger. The end point can be managed using Python SDK. 

Using Azure ML Python SDK, the ML pipeline can be built, deploy, and consume in Azure ML notebooks. An AutoML run is configured using SDK and the AutoML run identifies best model. Deploying the model creates a HTTP service, which can be consumed by clients. The service endpoints can be managed using SDK. The endpoint can be inspected using swagger to understand the signature of the service and its request and response structures.

## Dataset Summary
The dataset contains data about marketing compaigns of bank. The label indicates whether the customer subcribed after the campaign. The goal is to build a classification model that predicts if the client will subscribe or not.  The data contains demographic information of the client such as age, job, marital status and education along with finacial information such as housing, loan. Each record for the customer contains information related to participation in previous campaigns, when he was last contacted ..etc.

## Architectural Diagram
The lifecycle of machine learning model invloves data acquisition, data preparation, hypothesis and model development, model evaluation, model deployment, operations and optimization of the model. Azure Machine Learning uses DevOps based MLOps(Machine Learning Opearations) approach for meaching leaning workflows. MLOps applies applies continuous integration, delivery and deployment to the nachine learning process. 

![Architecture](azureml2_arch.png)

An Azure ML pipeline contain steps from data preparation to feature extraction to hyper parameter tuning to model evaluation. The Azure ML pipelines can be build, deployed and managed using Azure Machine Learning Studio UI. The Azure ML pipelines can be build, deployed and managed using Azure ML SDK.

## Key Steps
### Using Machine Learning Studio

![Dataset](azureml2_dataset.png)
![AzureML run](azureml2_run.png)
![AzureML run summary](azureml2_run_summary.png)
![Best Run](azureml2_bestrun.png)
![Deploy](azureml2_deploy.png)
![Endpoint](azureml2_endpoint.png)
![Endpoint logs](azureml2_endpoint_logs.png)
![Swagger1](azureml2_endpoint_swagger1.png)
![Swagger2](azureml2_endpoint_swagger2.png)
![Endpoint Results](azureml2_endpoint_results.png)
![Endpoint benchmark1](azureml2_endpoint_benchmark1.png)
![Endpoint benchmark2](azureml2_endpoint_benchmark2.png)

### Using Python SDK

![Pipeline](azureml2_nb_pipelines.PNG)
![Pipeline Details](azureml2_nb_pipeline_details.png)
![Pipeline Dataset](azureml2_nb_dataset.png)
![Run Widget](azureml2_nb_runwidget.png)
![Run Widget Complete](azureml2_nb_runwidget_complete.png)
![Pipeline Endpoint](azureml2_nb_endpoint.png)
![Pipeline Endpoint Run](azureml2_nb_endpoint_run.png)
![Pipeline Endpoint RunDetails](azureml2_nb_endpoint_rundetails.png)
![Pipeline Endpoint Completed](azureml2_nb_endpoint_completed.png)

*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
