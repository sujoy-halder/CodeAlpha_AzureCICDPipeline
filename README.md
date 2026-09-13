\# CodeAlpha DevOps Task 1 - Azure CI/CD Pipeline



\## Project Overview

This project demonstrates an automated CI/CD pipeline using Azure DevOps, Docker, Azure Container Registry, and Azure App Service.



Whenever code is pushed to the main branch, Azure Pipelines automatically builds a Docker image, pushes it to Azure Container Registry, and deploys the updated container to Azure App Service.



\## Live Application

https://sujoy-codealpha-cicd.azurewebsites.net



\## GitHub Repository

https://github.com/sujoy-halder/CodeAlpha\_AzureCICDPipeline



\## Tools Used

\- GitHub

\- Docker

\- Azure CLI

\- Azure DevOps

\- Azure Pipelines

\- Azure Container Registry

\- Azure App Service

\- Nginx



\## Project Architecture

GitHub -> Azure Pipelines -> Azure Container Registry -> Azure App Service



\## Pipeline Stages

1\. Build and Push Docker Image

2\. Deploy to Azure App Service



\## Files

\- Dockerfile

\- azure-pipelines.yml

\- site/index.html



\## Output Proof

\- Local Docker website tested on localhost:8080

\- Azure Pipeline build stage completed successfully

\- Azure Pipeline deploy stage completed successfully

\- Application deployed successfully on Azure App Service



\## Learning Outcome

I learned how to create a Dockerized web application, push source code to GitHub, build a CI/CD pipeline using Azure DevOps, store Docker images in Azure Container Registry, and deploy containers to Azure App Service.

