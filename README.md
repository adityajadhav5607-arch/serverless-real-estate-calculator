Serverless Real Estate Profit Calculator
A simple web application to help analyze potential rental property investments by calculating key financial metrics like loan amount, monthly mortgage, and net monthly profit/loss, with all calculations and data persistence handled by a robust serverless backend on AWS.

Live Demo
Click here to launch the application!
https://staging.d21ag7f7nooyzf.amplifyapp.com/

Key Features
Interactive Frontend: User-friendly interface to input real estate financial parameters.

Serverless Calculations: Efficient and scalable backend processing of all financial computations using AWS Lambda.

Data Persistence: Automatically saves each calculation to a DynamoDB database for future reference.

Fully Cloud-Native: Built entirely using modern AWS serverless services, ensuring high availability, scalability, and cost-effectiveness.

Tech Stack
This project leverages a powerful serverless architecture on Amazon Web Services (AWS):

Frontend Hosting: AWS Amplify

Hosts the static web application (HTML, CSS, JavaScript).

Provides a streamlined continuous deployment pipeline.

Backend API: Amazon API Gateway

Acts as the secure and scalable entry point for all frontend requests to the backend.

Routes calculation requests to the Lambda function.

Backend Logic: AWS Lambda (Python)

A serverless compute service that executes the core financial calculation logic.

Eliminates the need to manage servers.

Database: Amazon DynamoDB

A fully managed NoSQL database service used to store all submitted calculation data.

Ensures high performance and scalability for data persistence.

Architecture Diagram
Here's a visual representation of the application's architecture:
https://photos.google.com/share/AF1QipOCMMliog5Bw7wjxOF0aNZMVe6ufl86CSkRKdNRESEnSCH3bagHRfUMBSOjnHgFpQ?key=Ykg0bnBLUm1lUE9PMW51OTZkUGxScVIxaDBxV3dn

Flow Explanation:

The User interacts with the web application hosted on AWS Amplify.

Input data is sent via an HTTP POST request from Amplify to Amazon API Gateway.

API Gateway invokes the AWS Lambda function.

The Lambda function performs the calculations and saves the data to Amazon DynamoDB.

Lambda returns the calculation results to API Gateway, which then sends them back to the Amplify frontend.

Amplify displays the results to the User.


Contact
Feel free to connect with me:

LinkedIn: https://www.linkedin.com/in/aditya-jadhav-68190a254/
Email: adityajadhav5607@gmail.com
