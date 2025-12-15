# BUG-001

## Title
Login form allows submit with empty password

## Steps to Reproduce
1. Open Login page
2. Enter username
3. Leave password empty
4. Click Login

## Actual Result
Form is submitted, request is sent

## Expected Result
Validation error should be shown, request should not be sent

## Severity
Major

## Priority
High