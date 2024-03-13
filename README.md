## Project: Read from Azure SQL Database from DevOps using federated-credentials

**Project Description**: This project will read from a table in SQL Database, connecting using a token for federated credentials.

## Create pipeline

* Create new project in Azure DevOps.

* Create pipeline then connect to existing repo in GitHub and select YAML file.

* In the Project Settings, create service connection to your Azure Subscription called azure_connection:

This creates App registration with Federated credentials. Please note this is a POC so creating the App registration is fine, however, in Production it is likely that this will be performed separately prior to the creation of the pipeline.

![Create service connection 1](/screenshots/Create_service_connection_1.png)

![Create service connection 2](/screenshots/Create_service_connection_2.png)

![Create service connection 2](/screenshots/Create_service_connection_3.png)

