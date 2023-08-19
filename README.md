# BookManagement-on-AWS

Welcome to the Book Management App Deployment project! In this guide, we'll walk you through the steps to deploy your Book Management app to Amazon Web Services (AWS). This deployment leverages various AWS services to ensure scalability, reliability, and ease of management. Whether you're new to AWS or an experienced developer, this README will provide you with detailed instructions to successfully deploy your app.
Table of Contents

## Overview
## Prerequisites
  Step-by-Step Deployment
      Step 1: Prepare Your App and GitHub Repository
      Step 2: Set Up AWS Environment
      Step 3: Launch Instances Using Auto Scaling Group
      Step 4: Set Up Application Load Balancer (ALB)
      Step 5: Configure Systemd for App Management
      Step 6: Test Your Setup
      Step 7: Add EC2 IP Address Endpoint
      Step 8: Create README and Documentation
    `Bonus`: Scaling Policy Configuration
    Contributing
    License

## Overview

This project aims to deploy the Book Management app, a REST API built using Express.js, to AWS with optimal scalability and reliability. The app will be deployed in an Auto Scaling Group behind an Application Load Balancer. It will be managed using systemd, and a bonus step includes setting up scaling policies to utilize the Average CPU utilization metric.
Prerequisites

Before you begin, ensure you have the following:

    -A functional Book Management app with necessary code and dependencies.
    -An AWS account with appropriate access permissions.
    -Basic familiarity with AWS services, Git, and the command line.

Step-by-Step Deployment

Follow the detailed steps provided in the DEPLOYMENT GUIDE to deploy your Book Management app on AWS. The guide includes terminal commands, configuration details, and screenshots for each step.
Step 1: Prepare Your App and GitHub Repository

    - Make sure your Book Management app is fully functional with code and dependencies.
    - Create a public GitHub repository for your project if not done already.
    - Upload the app.tar.gz file containing package.json, package-lock.json, and the dist directory to a GitHub release.

Step 2: Set Up AWS Environment

    Log in to your AWS account and navigate to the AWS Management Console.
    Create an EC2 key pair for SSH access.
    Set up security groups for instances and the Application Load Balancer.



Continue following the step-by-step instructions in the DEPLOYMENT GUIDE for the remaining deployment steps.
Bonus: Scaling Policy Configuration

To enhance your deployment, the bonus step covers setting up scaling policies using the Average CPU utilization metric to ensure efficient utilization of resources.

Learn more about scaling policies
Contributing

Contributions to this project are welcome! If you find issues or have improvements, please open an issue or pull request.
License

This project is licensed under the MIT License.

By following this guide, you'll successfully deploy your Book Management app on AWS, utilizing the power of cloud infrastructure while ensuring scalability and reliability. Feel free to tailor this README to your project's specifics and add any additional information that may be relevant. Happy deploying!
