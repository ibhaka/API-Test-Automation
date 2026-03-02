# API-Test-Automation

# 🚀 Restful-Booker API Test Automation

This project is a Java-based API test automation framework designed to perform end-to-end testing for the [Restful-Booker](https://restful-booker.herokuapp.com/) API service.

## 🛠 Tech Stack

* **Language:** Java 17+
* **API Library:** [RestAssured](https://rest-assured.io/)
* **Test Runner:** [TestNG](https://testng.org/)
* **Reporting:** [Allure Report](https://docs.qameta.io/allure/)
* **Build Tool:** Maven

---

## 📋 Test Scenarios

The project covers all primary endpoints as per the API documentation:

| Step | Test Case | HTTP Method | Description |
| :--- | :--- | :--- | :--- |
| 1 | **Create Token** | `POST` | Generates an auth token for administrative access. |
| 2 | **Get Booking IDs** | `GET` | Retrieves a list of all existing booking IDs. |
| 3 | **Create Booking** | `POST` | Creates a new booking and stores the generated ID. |
| 4 | **Get Booking** | `GET` | Verifies the details of the created booking by ID. |
| 5 | **Update Booking** | `PUT` | Performs a full update of the booking details. |
| 6 | **Partial Update** | `PATCH` | Updates specific fields of the existing booking. |
| 7 | **Delete Booking** | `DELETE` | Removes the created booking from the system. |
| 8 | **Health Check** | `GET` | Confirms the API service is up and running (Ping). |

---

## 🚀 Setup and Execution

### 1. Prerequisites
* **Maven** must be installed on your system.
* **Java JDK 11** or higher is required.
* **Allure Commandline** is required to generate and view reports.

### 2. Run Tests
To execute all tests via the terminal:
```bash
mvn clean test

