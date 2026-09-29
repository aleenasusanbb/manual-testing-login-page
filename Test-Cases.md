# Login Page – Manual Test Cases

## Project Overview

This project demonstrates manual testing of a sample login page. The purpose is to verify that users can successfully log in with valid credentials and that appropriate validation messages are displayed for invalid inputs.

## Test Environment

* **Application:** Sample Login Page
* **Testing Type:** Manual Testing
* **Testing Approach:** Functional Testing
* **Browser:** Google Chrome
* **Test Status:** Practice Project

## Test Cases

| Test Case ID | Test Scenario                      | Test Steps                                                | Test Data                         | Expected Result                                 |
| ------------ | ---------------------------------- | --------------------------------------------------------- | --------------------------------- | ----------------------------------------------- |
| TC-001       | Login with valid credentials       | Enter valid username and password and click Login         | Valid username + valid password   | User should be logged in successfully           |
| TC-002       | Login with invalid username        | Enter invalid username and valid password and click Login | Invalid username + valid password | Appropriate error message should be displayed   |
| TC-003       | Login with invalid password        | Enter valid username and invalid password and click Login | Valid username + invalid password | Appropriate error message should be displayed   |
| TC-004       | Login with both fields empty       | Leave username and password empty and click Login         | Blank fields                      | Validation message should be displayed          |
| TC-005       | Login with empty username          | Leave username empty and enter password                   | Blank username + valid password   | Username validation message should be displayed |
| TC-006       | Login with empty password          | Enter username and leave password empty                   | Valid username + blank password   | Password validation message should be displayed |
| TC-007       | Password masking                   | Enter a password in the password field                    | Sample password                   | Password characters should be masked            |
| TC-008       | Login button functionality         | Enter valid credentials and click Login                   | Valid credentials                 | Login button should submit the login request    |
| TC-009       | Username field accepts valid input | Enter a valid username                                    | Valid username                    | Username should be accepted                     |
| TC-010       | Password field accepts valid input | Enter a valid password                                    | Valid password                    | Password should be accepted                     |

## Testing Notes

These test cases are created as part of a manual testing practice project. Actual Pass/Fail results will depend on the login application being tested.
