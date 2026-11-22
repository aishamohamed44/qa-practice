# Practice Test Cases: Swag Labs Login Page

⚠️ **Practice exercise** - these are example test cases I wrote while learning. The test target is [saucedemo.com](https://www.saucedemo.com), a free demo site made for testing practice.

**Feature under test:** Login page
**Test type:** Manual, functional
**Written by:** Aisha Madny (learning exercise)

| ID | Title | Steps | Test data | Expected result |
| -- | ----- | ----- | --------- | --------------- |
| TC-01 | Login with valid user | 1. Open saucedemo.com 2. Enter username 3. Enter password 4. Click Login | username: `standard_user`, password: `secret_sauce` | User goes to the Products page |
| TC-02 | Login with wrong password | 1. Open saucedemo.com 2. Enter valid username 3. Enter wrong password 4. Click Login | username: `standard_user`, password: `wrong123` | Error message shows: "Username and password do not match any user in this service" |
| TC-03 | Login with empty username | 1. Open saucedemo.com 2. Leave username empty 3. Enter password 4. Click Login | password: `secret_sauce` | Error message shows: "Username is required" |
| TC-04 | Login with empty password | 1. Open saucedemo.com 2. Enter username 3. Leave password empty 4. Click Login | username: `standard_user` | Error message shows: "Password is required" |
| TC-05 | Login with locked out user | 1. Open saucedemo.com 2. Enter locked user 3. Enter password 4. Click Login | username: `locked_out_user`, password: `secret_sauce` | Error message shows: "Sorry, this user has been locked out." |
| TC-06 | Logout after login | 1. Login with valid user 2. Open the menu (top left) 3. Click Logout | username: `standard_user`, password: `secret_sauce` | User goes back to the Login page |

## What I practiced here

- Writing preconditions, steps and expected results in a clear way
- Testing both positive cases (TC-01, TC-06) and negative cases (TC-02 to TC-05)
- Using the test data the demo site gives on its login page
