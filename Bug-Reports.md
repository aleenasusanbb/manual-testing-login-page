# Login Page – Bug Reports

## Project Overview

This document contains sample bug reports created as part of a manual testing practice project.

## Bug Report 1

**Bug ID:** BUG-001

**Bug Title:** Login button accepts empty fields

**Severity:** Medium

**Priority:** High

**Environment:** Google Chrome

### Steps to Reproduce

1. Open the login page.
2. Leave the username field empty.
3. Leave the password field empty.
4. Click the **Login** button.

### Expected Result

The application should display appropriate validation messages for the required fields.

### Actual Result

The application allows the login action without displaying the required field validation.

### Status

Open

---

## Bug Report 2

**Bug ID:** BUG-002

**Bug Title:** Password is displayed as plain text

**Severity:** Medium

**Priority:** Medium

**Environment:** Google Chrome

### Steps to Reproduce

1. Open the login page.
2. Click the password field.
3. Enter a password.

### Expected Result

The password should be masked using dots or other hidden characters.

### Actual Result

The password is displayed as plain text.

### Status

Open

---

## Bug Report 3

**Bug ID:** BUG-003

**Bug Title:** Invalid login does not display an error message

**Severity:** Medium

**Priority:** High

**Environment:** Google Chrome

### Steps to Reproduce

1. Open the login page.
2. Enter an invalid username.
3. Enter an invalid password.
4. Click the **Login** button.

### Expected Result

An appropriate error message should inform the user that the login credentials are invalid.

### Actual Result

No clear error message is displayed.

### Status

Open

## Testing Note

These are sample defects created for a manual testing portfolio project. They are intended to demonstrate the format and structure of a professional bug report.
