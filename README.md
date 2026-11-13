# Azure App Service CI/CD Automation Using GitHub Actions

**Technologies:** Microsoft Azure | GitHub Actions | Azure App Service | Microsoft Entra ID | HTML | CSS | JavaScript | YAML | Visual Studio Code

## Introduction

This project demonstrates the implementation of an automated Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions to deploy a web application to Microsoft Azure App Service.

The project involved developing a basic website using HTML, CSS and JavaScript, hosting the source code on GitHub, configuring Azure App Service with a staging deployment slot, and implementing GitHub Actions workflows to automate website validation and deployment.

Secure authentication between GitHub Actions and Microsoft Azure was configured using Microsoft Entra ID application registration and federated credentials, eliminating the need to store Azure client secrets for authentication.

The deployment process was designed to validate application files, package the website as an artifact, and deploy the application to the Azure App Service staging slot.

The project also involved troubleshooting deployment failures, correcting configuration errors, and verifying the successful deployment of the application.

## Project Preview

The following screenshot shows the successfully
deployed website hosted on Azure App Service.

![Deployed Website](screenshots/01-deployed-website.png)
