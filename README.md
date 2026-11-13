# Azure-App-Service-CI-CD
Azure App Service CI/CD Pipeline Using GitHub Actions

Introduction:

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions and Microsoft Azure App Service.
The objective was to automate the website validation and deployment process by integrating a GitHub repository with Azure App Service.

The project uses GitHub Actions to validate website files, package the application as an artifact, and deploy it to an Azure App Service staging slot. Secure authentication between GitHub Actions and Azure is configured using OpenID Connect (OIDC) with Microsoft Entra ID, eliminating the need to store Azure credentials as plain-text secrets.

The implementation also demonstrates practical experience with Git branching, pull requests, reusable GitHub Actions workflows, artifact management, Azure resource configuration, and troubleshooting deployment issues.
