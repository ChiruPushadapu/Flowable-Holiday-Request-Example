# Flowable Holiday Request Process Example
This project serves as a tutorial for creating a Flowable process engine and implementing a simple holiday request process. It provides an introduction to core concepts and demonstrates how to work with the Flowable API.

## Overview
In this tutorial, we build a holiday request process that involves the following steps:

1. Employee Holiday Request: Employees submit requests specifying the number of days they wish to take off.

2. Manager Approval: Managers review and either approve or reject the requests.
3. External System Integration: Simulated registration of requests in an external system.
4. Email Notifications: Automated email notifications are sent to employees with the outcome of their requests.

## Getting Started
To run the project locally, follow these steps:

1. ### Clone the Repository:

git clone https://github.com/ChiruPushadapu/flowable-holiday-request-example.git

2. ### Set Up application.properties:

Create an application.properties file in the src/main/resources directory.
Add your credentials and configuration details.

3. ### Build and Run:

mvn clean install
java -jar target/flowable-holiday-request-example.jar

4. ### Access the Application:
Open a web browser and go to http://localhost:8080 to interact with the holiday request application.

## Technologies Used
1. Java
2. Flowable Process Engine
3. Maven

## Contributing
Contributions are welcome! Please feel free to fork this repository and submit pull requests to suggest improvements or fix any issues.
