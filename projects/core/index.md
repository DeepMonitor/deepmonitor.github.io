[Back to home](/)

# Core Project `Version 0.1`
We built it to be a secure and fast web server to manage users, employees, and products.

## Database Models

- [`Employee`](/projects/core/models/employee)
- [`User`](/projects/core/models/user)
- `Ticket`

## Public Routes

#### Action by Employee
- `Routes::Employee_Self_Signin`
- `Routes::Employee_Self_Signout`
- `Routes::Employee_Self_PR`
- `Routes::Employee_Self_PR_Verify`
- `Routes::Employee_Self_View`
- `Routes::Employee_Self_Update`
- `Routes::Employee_Self_Update_Password`
- `Routes::Employee_Users_View`
- `Routes::Employee_Users_Search`
- `Routes::Employee_Users_Create`
- `Routes::Employee_Users_Update`
- `Routes::Employee_Users_Delete`
- `Routes::Employee_Tickets_Create`
- `Routes::Employee_Tickets_View`
- `Routes::Employee_Tickets_Search`
- `Routes::Employee_Tickets_Answer`
- `Routes::Employee_Tickets_Close`

#### Action by User

- `Routes::User_Self_Signup`
- `Routes::User_Self_Signup_Verify`
- `Routes::User_Self_Signin`
- `Routes::User_Self_Signout`
- `Routes::User_Self_PR`
- `Routes::User_Self_PR_Verify`
- `Routes::User_Self_View`
- `Routes::User_Self_Update`
- `Routes::User_Self_Update_Password`
- `Routes::User_Tickets_View`
- `Routes::User_Tickets_Search`
- `Routes::User_Tickets_Answer`
- `Routes::User_Tickets_Close`

## Functions

- `Core::Validate_Employee_Authentication`
- `Core::Validate_User_Authentication`
- `Core::Validate_User_Name`
- `Core::Validate_User_Email`
- `Core::Validate_User_Username`
- `Core::Validate_User_Password`
- `Core::Validate_User_Token`
- `Core::Validate_Ticket_Title`
- `Core::Validate_Ticket_Description`

## Changelogs

- [`0.1 - LIVE`](/projects/core/changelogs/0.1)
