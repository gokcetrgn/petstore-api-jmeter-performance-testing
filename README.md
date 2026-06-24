# JMeter Petstore API Testing Project

## Overview

This project demonstrates API testing using Apache JMeter on the Swagger Petstore API. The test plan covers the main CRUD operations (Create, Read, Update, Delete) and validates API responses using assertions.

## Test Scenarios

### Create Pet (POST)

Creates a new pet record and verifies that the API returns the correct information.

### Get Pet (GET)

Retrieves the created pet and validates the response data.

### Update Pet (PUT)

Updates the pet information and verifies that the changes are successfully applied.

### Delete Pet (DELETE)

Deletes the pet record and confirms successful removal.

## Test Components

* Thread Group
* HTTP Request Defaults
* HTTP Header Manager
* HTTP Requests (POST, GET, PUT, DELETE)
* Response Assertions
* Summary Report

## Tools Used

* Apache JMeter
* Swagger Petstore API

## Project Structure

```text
.
├── petstore-api-jmeter-performance-testing.jmx
├── README.md
└── screenshots/
```

## Screenshots

Screenshots of the test plan and execution results are available in the `screenshots` folder.

## Author

Gökçenaz Torgan
