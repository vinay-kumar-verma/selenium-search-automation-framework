# Selenium Search Automation Framework

A robust test automation framework built using Java, Selenium WebDriver, TestNG, and the Page Object Model (POM) design pattern. The framework automates search validation workflows across multiple Google Search content categories and demonstrates scalable automation architecture used in real-world testing environments.

## Features

* Page Object Model (POM) architecture
* Cross-browser execution support
* Automated search validation workflows
* Data-driven testing using TestNG
* Extent Reports integration
* Reusable and maintainable framework design
* Exception handling and synchronization mechanisms
* WebDriverManager integration for driver management

## Tech Stack

### Languages

* Java

### Automation Tools

* Selenium WebDriver
* TestNG

### Design Patterns

* Page Object Model (POM)

### Build & Dependency Management

* Maven
* WebDriverManager

### Reporting

* Extent Reports

## Test Coverage

The framework validates search functionality across multiple Google Search content sections, including:

* All
* News
* Images
* Videos

Coverage includes:

* Search result validation
* Dynamic web element handling
* Cross-browser execution
* UI workflow verification
* Negative and edge-case scenarios

## Framework Architecture

```text
src
│
├── pages
│   ├── HomePage.java
│   ├── SearchResultsPage.java
│
├── tests
│   ├── SearchTests.java
│
├── utilities
│   ├── DriverFactory.java
│   ├── ConfigReader.java
│   ├── ReportManager.java
│
├── resources
│   ├── config.properties
│
└── reports
```

## Key Automation Concepts Demonstrated

* Page Object Model (POM)
* TestNG Lifecycle Management
* Explicit Waits
* Exception Handling
* Data-Driven Testing
* Reusable Utilities
* Reporting and Logging
* Cross-Browser Testing

## Getting Started

### Prerequisites

* Java 17+
* Maven
* Chrome or Firefox

### Clone Repository

```bash
git clone https://github.com/vinay-kumar-verma/selenium-search-automation-framework.git
```

### Execute Tests

```bash
mvn clean test
```

## Sample Report

Add screenshots of:

* Test Execution
* Extent Report Dashboard
* Pass/Fail Summary

## Future Enhancements

* Jenkins CI/CD Integration
* Parallel Execution
* Dockerized Test Execution
* Selenium Grid Support
* Cloud Browser Execution

## Author

Vinay Kumar Verma

QA Automation Engineer | Java | Selenium | TestNG | Oracle SQL | REST API Testing
