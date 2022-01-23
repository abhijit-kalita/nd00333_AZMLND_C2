*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Operationalizing an ML project

The aim of the project is to operationalize an Ml pipeline. We start with a bank marketing dataset, run automl process
to obtain a model with high accuracy, deploy this model as a rest endpoint with swagger enabled, enable logging for the project,
Consume and test the end point if he entire process is well implemented.

## Architectural Diagram
The diagram below explains the architecture of the project.
The process can be divided into two main parts as in a typical ML lifecycle. 
First is That of getting the data and training a model.
Second is that of getting the model and puuting it behind a rest end point for consumption. This is done using the azure container infrastructure

![Architecture diagram](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/Project_Architecture.png)


## Key Steps
key steps of the process are 
* Ingestion of a dataset

![Dataset](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/Bankmktng_Dataset.png)

* Execution of a ML process with the help of Azure AutoML

![Automl completed](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/Automl_completed_exp.png)4

* Get the best model of automl process

![Best Automl model](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/Automl_Best_exp.png)

* Enable swagger for the end point

![Swagger1](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/swagger.sh-run.png)

![Swagger2](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/swaggerjspn-access-local.png)


* Enable logging and application insights

![App Insignts](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/Enabling_app_Insights2.png)

* Deploy the model as a rest end point using a pipeline script

![Rest endpoint](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/pipeline-restendpoint.png)

* Test the consumption of the end point

![Rest endpoint consumption](https://github.com/abhijit-kalita/nd00333_AZMLND_C2/blob/master/starter_files/images/consume-endpoint.png)


## Screen Recording
[Screencast Link of Project](https://link-url-here.org)

## Standout Suggestions
Some improvements which can be attemped are
Automate a scheduled test of the rest end point to check if the performance degrades and launch a retraining based on that

