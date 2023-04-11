
# Basic Application Development 

This project will created a 3-Tier Application which will be deployed in AWS Cloud Environment.
The Purpose of this small project is to get hands-on experience regarding web application development. In this project, many of the tasks are done in a very pragmatic way, to let the contributor to build a simple application using developed technologies.

## Timeline

This project will (planned) take up to 6 months with a workload of 5-6 Hours/month.
This will start in May 2023
## Business case

An HR employee want to update the data of the worker in her company. To do this she has to login into the application and afterwards she can update the worker database. Although she can only update the worker database for the company branch where she is employed. To separate the access to specific database there is an authencation service (login) that will allow an HR to access database in her branch. 
<br>The workflow are like following:
1. HR in Branch 1 login into the Application with her "credentials-Branch-1"
2. After she logged in, she can only access the database for the Branch 1 and can not see the worker data from another branch.

## Three-Tier Application Architecture

A common architectural example that implements best practices for Application Layer which breaks an Application into three layers:

- Presentation layer => a public accessible layer that exposes to the internet

- Application layer => this layer containes computing and private API that routes requests from the presentation layer to the database layer.

- Database layer => this layer containes business critical-services such as relational or non-relational database.

The architecture will be looked like below diagram.

![architecture diagram](/img/aws-kmki-proj.png)

The development will be divided mainly into three main areas:
1. Frontend
2. Backend + Database
3. Infrastructure

# This is a project to have a good learning experience for everyone with interest in application development. Don't be scared to make mistakes.
## Frontend Development
In this area you will develop a static website for the development as well as deploying an authentication service.
The technologies you might use:
- React (JavaScript or TypeScript)
- Angular
- Authentication Service e.g : AWS Cognito, JWT
- HTML
- CSS
- Git, Github
## Backend and Database Development
In this area you will develop backend services (API and Database).
The technologies you might use:
- Python (FastAPI or Flask)
- Javascript (NodeJS)
- REST API
- Relational Database (PostgreSQL or MySQL)
- Non relational Database (MongoDB or Cassandra)
- JWT
- Git, Github
- Docker

## Infrastructure Development
In this area you will develop infrastructure in the AWS Cloud.
The technologies you might use:
- Terraform or CloudFormation
- Github Action
- CI/CD Pipeline
- Bash scripting
- Linux
- AWS services
