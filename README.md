# Vite/React AWS Deployment

This repository contains a Vite/React application to demonstrate the process of deploying a React app to AWS from a Git repository. The guide includes steps for both public and private repositories.

## Table of Contents

- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Setup Instructions](#setup-instructions)
    - [Public Repository Deployment](#public-repository-deployment)
    - [Private Repository Deployment](#private-repository-deployment)
- [Testing the Deployment](#testing-the-deployment)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Project Overview

This project is a simple React application created with Vite. It serves as a template for deploying React applications to AWS, showcasing the deployment process from both public and private Git repositories.

## Prerequisites

- AWS account with necessary permissions to create resources
- Git installed on your local machine
- AWS CLI installed and configured
- Node.js and npm installed

## Setup Instructions

### Public Repository Deployment

1. **Clone the Repository**

    ```sh
    git clone https://github.com/yourusername/vite-react-aws-deployment.git
    cd vite-react-aws-deployment
    ```

2. **Install Dependencies**

    ```sh
    npm install
    ```

3. **Build the Application**

    ```sh
    npm run build
    ```

4. **Deploy to AWS**

    - Follow the AWS documentation to deploy the built application to an AWS service like S3 or Amplify.

### Private Repository Deployment

1. **Clone the Repository**

    Ensure you have access to the private repository. Use the following command:

    ```sh
    git clone git@github.com:yourusername/private-vite-react-aws-deployment.git
    cd private-vite-react-aws-deployment
    ```

2. **Install Dependencies**

    ```sh
    npm install
    ```

3. **Build the Application**

    ```sh
    npm run build
    ```

4. **Deploy to AWS**

    - Follow the AWS documentation to deploy the built application to an AWS service like S3 or Amplify.
    - For private repositories, you may need to configure your CI/CD pipeline to handle authentication.

## Testing the Deployment

After deployment, ensure your application is working correctly by visiting the provided AWS URL.

## Troubleshooting

- **Build Issues:** Ensure all dependencies are installed correctly. Use `npm install` to reinstall.
- **Deployment Issues:** Check AWS permissions and service configurations. Review the AWS deployment logs for specific errors.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
