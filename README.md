# CircleCI Deploy Markers Demo

A simple sample project demonstrating CircleCI Deploy Markers functionality.

## Overview

CircleCI Deploy Markers track deployment activities, logging all deployments in one place and connecting them to CI/CD pipelines.

## Branch Structure

This repository shows two different implementations of Deploy Markers:

- **`auto-detection` branch**: Job name-based automatic detection
- **`manual-setup` branch**: Manual setup with step-by-step status tracking

## Automatic Detection (`auto-detection` branch)

- Markers automatically created when job name contains 'deploy'
- Works without additional configuration
- Only created when jobs successfully complete

## Manual Setup (`manual-setup` branch)

- Explicitly creates markers at each deployment stage
- Enables detailed step-by-step status updates
- No job name constraints

## Checking Automatic Detection Settings

1. In CircleCI web app, go to 'Organization settings' > 'Deploys'
2. Or 'Project Settings' > 'Deploys' 
3. Check "Enable automatic deploy marker detection" option

## Additional Resources

- [CircleCI Deploy Markers documentation](https://circleci.com/docs/deploy/configure-deploy-markers/)
- [CircleCI Deploys overview](https://circleci.com/docs/deploy/deploys-overview/)