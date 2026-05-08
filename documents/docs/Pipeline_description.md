# Pipeline Description

## Build Stage
- Installs dependencies for both frontend and backend
- Runs linting and builds the application

## Hold Stage
- Requests manual approval before deployment. Good for some testing or review processes.

## Deploy Stage
- Deploys the frontend to S3
- Deploys the backend to Elastic Beanstalk
