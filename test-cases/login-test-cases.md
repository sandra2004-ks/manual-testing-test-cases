# Login Page Manual Testing

## Project Overview

This project demonstrates manual testing techniques for a sample login page. It includes positive and negative test scenarios, expected results, and test execution status.

## Testing Objective

To verify that the login functionality accepts valid credentials and handles invalid or empty inputs correctly.

## Test Environment

- Testing type: Manual Testing
- Application: Practice login page
- Browser: Google Chrome
- Test data: Sample credentials only

## Test Cases

| Test Case ID | Test Scenario          | Test Steps                                          | Expected Result                                            |
|--------------|------------------------|-----------------------------------------------------|------------------------------------------------------------|
| TC_LOGIN_001 | Valid login            | Enter valid credentials and click Login             | User should log in successfully                            |
| TC_LOGIN_002 | Invalid password       | Enter a valid username and incorrect password       | An appropriate error message should appear                 |
| TC_LOGIN_003 | Empty fields           | Leave username and password empty, then click Login | Required-field validation should appear                    |
| TC_LOGIN_004 | Empty username         | Enter a password without a username                 | Username validation should appear                          |
| TC_LOGIN_005 | Empty password         | Enter a username without a password                 | Password validation should appear                          |
| TC_LOGIN_006 | Password masking       | Type a password in the password field               | Password characters should be masked                       |
| TC_LOGIN_007 | Logout                 | Log in and click Logout                             | User should be logged out                                  |
| TC_LOGIN_008 | Repeated invalid login | Submit invalid credentials multiple times           | Application should respond according to its security rules |

## Test Execution Results

Execution status: Not Run

Actual results: To be recorded after executing the tests on a practice application.

## Defect Reporting

Record any defects found with the following details:

- Bug ID
- Bug title
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity and priority
- Screenshot or supporting evidence

## Conclusion

This project is intended to demonstrate beginner-level manual testing documentation. Test results and defect reports will be updated after actual execution.
