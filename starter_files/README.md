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
* Execution of a ML process with the help of Azure AutoML
* Make sure that the pipeline is executed to completion
* Obtain the best performing model based on the AutoMl process
* Deploy the model as a rest end point
* Enable swagger for the end point
* Enable logging and application insights
* Test the consumption of the end point

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
