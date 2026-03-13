# Test Plan - SauceDemo Web Application

## 1. Introduction
This test plan describes testing approach for the SauceDemo Web Application. The objective is to validate the core functionality of the system including login, product management, cart functionality, checkout process and logout.

Testing will include manual testing, regression testing and user acceptance testing (UAT).


## 2. Test Scope

### In Scope
- Login functionality
- Invalid login validation
- Locked user login restriction
- Product list display
- Add products to cart
- Remove products from cart
- Cart page functionality
- Checkout process
- Checkout validation errors
- Order overview
- Order completion
- Logout functionality

### Out of Scope
- Performance testing
- Security testing
- Mobile compatibility testing


## 3. Test Types

### Functional Testing
Functional testing will verify that the system works according to the defined requirements and supports the expected user workflows.

### Regression Testing
Regression testing will ensure that new changes or updates do not break existing functionality. Automation scripts will later be used to execute regression tests.

### User Acceptance Testing (UAT)
User acceptance testing will validate that the system supports the complete user workflow and meets expected user requirements.


## 4. Test Approach
Testing will be conducted using both manual testing and automation testing.

Manual testing will validate functional requirements through defined test cases.

Automation testing will later be implemented using Selenium with Python to automate critical regression scenarios such as login, cart operations and checkout.


## 5. Test Environment

Testing will be conducted in the following environment:

- Application: SauceDemo 
- URL: https://www.saucedemo.com 
- Browser: Google Chrome 
- Operating System: Windows 
- Testing Type: Manual and Automation 


## 6. Test Deliverables
- Test Plan
- Requirements Document
- Test Scenarios
- Test Cases
- Automation Scripts
- Test Execution Report


## 7. Entry Criteria
- Application is accessible
- Test environment is available
- Test scenarios and test cases are prepared


## 8. Exit Criteria
- All test cases are executed
- Test results are documented
- Critical defects are reported
