# Note:
This report was developed as part of Cohort 1. The project and repository were inspired by tutorials from Krish Naik on YouTube. 
A big thank you to Krish Naik for the valuable insights and guidance that made this project possible!

<br>

## End to End MAchine Learning Project



## Run from terminal:

docker build -t favidocker.azurecr.io/studentperformance:latest .
(mstudentperformance is the web app name, it can be any name you want to give your docker image)

docker login favidocker.azurecr.io

docker push favidocker.azurecr.io/studentperformance:latest



## Azure Deployment Guide:

    ## Azure Deployment:
    Initiate the Azure deployment process to set up your machine learning application.

    ## Azure Registry Setup:
    Establish the Azure Container Registry to streamline the storage and management of Docker container images.

    ## Docker Setup on Local Machine:
    Configure Docker on your local machine to enable containerization of your machine learning application.

    ## Push Docker to Container Registry (Azure):
    Push your Docker container to the Azure Container Registry, ensuring seamless accessibility for deployment.

    ## Create Azure Web App:
    Generate an Azure Web App to host and deploy your machine learning application.

    ## Pull Container Registry into Web App:
    Integrate the Azure Container Registry with the Azure Web App, facilitating the deployment process.

    ## Configure GitHub Actions for Deployment:
    Utilize GitHub Actions to automate the deployment process, ensuring a smooth and efficient workflow.

## This step-by-step guide provides a comprehensive walkthrough for deploying your machine learning application using Azure services, Docker, and GitHub Actions.
