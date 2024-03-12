# Flowable Holiday Request Process Example
This project serves as a tutorial for creating a Flowable process engine and implementing a simple holiday request process. It provides an introduction to core concepts and demonstrates how to work with the Flowable API.

## Overview
In this tutorial, we build a holiday request process that involves the following steps:

### Employee Holiday Request: Employees submit requests specifying the number of days they wish to take off.
### Manager Approval: Managers review and either approve or reject the requests.
### External System Integration: Simulated registration of requests in an external system.
### Email Notifications: Automated email notifications are sent to employees with the outcome of their requests.

## Getting Started
To run the project locally, follow these steps:

1. ### Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/flowable-holiday-request.git
Set Up application.properties:

2. ### Create an application.properties file in the src/main/resources directory.
Add your credentials and configuration details. (Remember not to commit sensitive information to the repository.)

3. ### Build and Run:

bash
Copy code
mvn clean install
java -jar target/flowable-holiday-request.jar

4. ### Access the Application:
Open a web browser and go to http://localhost:8080 to interact with the holiday request application.

## Technologies Used
Java
Flowable Process Engine
Maven

## Contributing
Contributions are welcome! Please feel free to fork this repository and submit pull requests to suggest improvements or fix any issues.

## License
This project is licensed under the MIT License.
