# DevOps CI/CD Automation Project

A comprehensive DevOps automation project demonstrating CI/CD pipeline implementation using Azure DevOps, featuring automated deployment workflows, structured project management, and integration with various Azure services.

## Project Overview

This project showcases the implementation of modern DevOps practices through automated CI/CD pipelines built with Azure DevOps. The solution includes frontend React applications with Redux state management, automated build and deployment processes, and comprehensive project management workflows.

## Key Features

- Automated CI/CD pipelines using Azure DevOps YAML workflows
- React frontend application with Redux state management
- Azure Web App deployment with Linux runtime
- Deployment ring configuration for staged releases
- Integration with Azure Artifacts for package management
- Slack notifications for deployment status
- Agile project management with structured backlogs

## Technology Stack

- Frontend: React, Redux, Node.js
- Cloud Platform: Microsoft Azure
- CI/CD: Azure DevOps Pipelines
- Runtime: Node.js 21.x on Ubuntu Linux
- Package Management: npm, Azure Artifacts
- Project Management: Azure DevOps Boards

## Architecture

The project implements a standard web application deployment pattern with automated testing, building, and deployment stages. The pipeline triggers on commits to the main branch and deploys to Azure Web Apps using Linux containers.

## Pipeline Configuration

The Azure DevOps pipeline includes:
- Build stage with Node.js environment setup
- Automated npm install and build processes
- Artifact creation and publishing
- Deployment stage with Azure Web App integration
- Environment-specific deployment configurations

## Project Management

Implemented agile methodologies using Azure DevOps Boards with:
- Structured epics and features organization
- Work item tracking and sprint planning
- Delivery flow optimization
- Team collaboration enhancement

## Getting Started

### Prerequisites

- Node.js 21.x or higher
- Azure subscription with Web App service
- Azure DevOps organization setup
- Git version control

### Local Development

1. Clone the repository
2. Install dependencies: `npm install`
3. Start development server: `npm start`
4. Build for production: `npm run build`

### Deployment

The application automatically deploys through the configured Azure DevOps pipeline when changes are pushed to the main branch. Manual deployments can be triggered through the Azure DevOps interface.

## Contributing

This project demonstrates DevOps best practices for educational and portfolio purposes. The implementation focuses on real-world application of CI/CD automation and agile project management methodologies.
