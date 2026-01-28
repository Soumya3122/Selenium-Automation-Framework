# Framework Architecture

## Selenium Automation Framework (Java + TestNG)

---

## Architecture Overview

This automation framework follows a modular and scalable architecture using the **Page Object Model (POM)** design pattern.  
It separates test logic from UI locators, improving maintainability and readability.

---

## Framework Components

### 1. Test Layer
- Contains TestNG test classes
- Responsible for executing test scenarios
- Validates application behavior using assertions

### 2. Page Layer (Page Object Model)
- Contains page classes for each application page
- Stores web element locators and page actions
- Enhances reusability and reduces code duplication

### 3. Base Layer
- Handles WebDriver initialization
- Manages browser setup and teardown
- Provides common utility methods

### 4. Utility Layer
- Screenshot capture
- Wait handling
- Test data reading
- Reusable helper methods

### 5. Configuration Layer
- Stores environment and browser configurations
- Centralized control of test settings

---

## Execution Flow

1. Test execution starts from TestNG XML
2. Browser is initialized from Base class
3. Page classes interact with web elements
4. Assertions validate expected results
5. Reports are generated after execution

---

## Tools & Technologies Used

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)

---

## Benefits of the Framework

- Easy maintenance
- High reusability
- Scalable architecture
- Interview-ready design
