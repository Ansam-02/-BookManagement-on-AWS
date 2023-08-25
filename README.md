# Book Management System App Deployment on AWS

Welcome to the Book Management System App Deployment tutorial! This guide will walk you through deploying your Book Management app on Amazon Web Services (AWS) using optimal practices for scalability and reliability.

![Book Management System](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/9f497e75-78ce-4622-8688-b9c629675faf)


## Prerequisites

Before you begin, make sure you have the following:

- A functional Book Management System app with code and dependencies.
- An AWS account with the necessary permissions.
- Basic familiarity with AWS services, Git, and the command line.

## Step-by-Step Deployment Guide

### Step 1: Prepare Your App and GitHub Repository

- Ensure your app code is ready and available on a GitHub repository.
![Screenshot from 2023-08-24 20-14-43](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/7aee5299-b4a6-4cc1-8897-47b461dc35cc)
![Screenshot from 2023-08-20 21-53-47](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/5d142c21-4b20-4781-8c11-8ee586ac47a2)
![Screenshot from 2023-08-19 23-27-15](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/55e1e5d5-a2b1-463d-9a43-1e1403756f5e)

- Make a package of dist, package.json and and package-lock.json and upload it in a github release.
![Screenshot from 2023-08-22 13-06-11](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/f6600dd4-8bc3-4481-b979-24f3f6d6923e)
![Screenshot from 2023-08-23 17-31-24](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/80605280-6e7e-462a-8125-8e9db96ec0a5)


### Step 2: Set Up AWS Environment

- Create an IAM role with necessary permissions.

### Step 3: Launch Instances Using Auto Scaling Group

- Create an Auto Scaling Group to launch instances.
- Configure launch template and instance settings.
![Screenshot from 2023-08-22 01-14-06](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/b74f4bfd-c127-4de0-8ee9-968d0dc332d3)

![add the user data you want](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/be7ddb1e-6e67-494a-bde9-d30f59b6418f)



### Step 4: Set Up Application Load Balancer (ALB)

- Create an Application Load Balancer to distribute traffic.
- Configure listeners and target groups.
  
 ![Screenshot from 2023-08-22 01-14-30](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/77c78aff-a01e-4c3d-a12e-d473ba201caa)

![Screenshot from 2023-08-22 01-03-12](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/8902521c-1a90-4d75-bcd6-4d617a52b878)



### Step 5: Configure Systemd for App Management

- SSH into instances and set up systemd service for app management.
- Start and test your app using systemd.
![Screenshot from 2023-08-22 17-22-13](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/baf9a754-d863-4a75-9c83-7daa0e3e70bc)

![Screenshot from 2023-08-22 15-20-09](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/cdbdaf8c-ab81-43a7-a342-a900ed62507a)


### Step 6: Test Your Setup

- Access your app through the ALB URL.
- Test its functionality to ensure proper deployment.
![Screenshot from 2023-08-17 22-48-41](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/ae5e9bdd-a9c9-4eda-ace3-fcf961982246)
![Screenshot from 2023-08-22 17-22-13](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/f36123a2-ec42-4b68-9a14-21faf7433706)
![Screenshot from 2023-08-23 17-12-07](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/b0da11ef-155d-43cc-a7d0-aea64a145052)

![Screenshot from 2023-08-25 17-45-36](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/2529559e-c272-4736-aebf-8772b6f1f8aa)
![Screenshot from 2023-08-22 13-39-23](https://github.com/Ansam-02/Deployment-BookManagement/assets/137777479/3b1b3a80-174b-472e-8bc5-61f12605602b)


## Conclusion

Congratulations! You have successfully deployed your Book Management System app on AWS. Enjoy the benefits of scalability, reliability, and ease of management.

For more information and troubleshooting, consult the AWS documentation and resources.

## Contributing

Feel free to contribute to this tutorial by making pull requests.


## Happy Deploying!
