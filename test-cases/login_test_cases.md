# Login Test Cases

| ID | Title | Steps | Expected Result |
|---|---|---|---|
| TC-LOGIN-001 | Login with valid credentials | 1) Open login 2) Enter valid creds 3) Click Login | User is logged in, redirected to dashboard |
| TC-LOGIN-002 | Login with invalid password | 1) Open login 2) Enter valid user + invalid pass 3) Login | Error message shown, user not logged in |
| TC-LOGIN-003 | Empty fields validation | 1) Open login 2) Leave fields empty 3) Login | Validation messages shown |