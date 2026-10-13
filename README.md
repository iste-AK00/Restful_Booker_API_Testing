**Restful Booker API Testing Project**

A comprehensive API testing project for the Restful Booker API, created using Postman and Newman. This project focuses on API functionality, response validation, HTTP status codes, response data, and automated test execution.

**Project Overview**
The purpose of this project is to validate the functionality and reliability of the Restful Booker API through automated API testing.

The project includes a Postman collection, environment configuration, automated test scripts, an HTML execution report, and an Excel-based test case inventory.
<img width="1899" height="1226" alt="screencapture-file-C-Users-Isteak-Ahmed-Downloads-Report-RestfulBooker-Report-html-2026-10-10-22_49_34" src="https://github.com/user-attachments/assets/4d6d55df-9191-4a6d-9b00-58dc2e9f82e1" />


**Key Features**
- **API Functional Testing:** Validates GET, POST, PUT, PATCH, and DELETE requests.
- **Authentication & Authorization:** Tests token-based authentication, cookies, and access control.
- **Positive & Negative Testing:** Verifies expected behavior for valid and invalid inputs.
- **Boundary & Input Validation:** Tests special characters, Unicode values, invalid dates, missing fields, and unusual inputs.
- **Security Testing:** Includes SQL injection and XSS payload checks, along with authorization-related scenarios.
- **CRUD Operations:** Tests booking creation, retrieval, updating, and deletion.
- **Automated Assertions:** Validates status codes, response headers, response bodies, data types, and response times.
- **Command-Line Execution:** Uses Newman to execute Postman collections outside the Postman interface.
- **HTML Reporting:** Generates detailed HTML test reports using Newman HTML Extra Reporter.

**Tools & Technologies**
- Postman
- Newman
- Newman HTML Extra Reporter
- REST API
- JSON
- JavaScript (Postman test scripts)
  
**Project Structure**
RestfulBooker-API-Testing/
│
├── README.md
├── .gitignore
│
├── collections/
│   └── RestfulBooker_Collection.json
│
├── environments/
│   └── RestfulBooker_Environment.json
│
├── reports/
│   └── RestfulBooker_Report.html
│
└── test-results/
    └── RestfulBooker_Test_Cases.xlsx

**Test Coverage**
The collection is designed to validate API behavior through request execution and response assertions.

Testing areas include:

HTTP status code validation

Response body validation

Response structure and data checks

JSON property and value validation

Authentication-related request validation

Booking-related API operations

Response-time checks where implemented

Negative and error-response validation where implemented

**Disclaimer:** This project uses the Restful Booker public demo API for learning and testing purposes. Test results may vary depending on API availability and environment behavior.
