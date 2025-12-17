# User Management System

This project uses HTML, CSS, MySQL, and PDO, and its purpose is to practice database usage. Object-oriented programming and MVC architecture were not used.

---

## Demo Images

### User Pages

| Login | Info | Edit | Register |
|-------|------|------|----------|
| <img src="public/image/login.png" width="120" alt="Login"> | <img src="public/image/info.png" width="120" alt="Info"> | <img src="public/image/edit.png" width="120" alt="Edit"> | <img src="public/image/register.png" width="120" alt="Register"> |

### Admin Pages

| Dashboard | Search | Edit Admin |
|-----------|--------|------------|
| <img src="public/image/admin_dashbord.png" width="120" alt="Admin Dashboard"> | <img src="public/image/admin_search.png" width="120" alt="Admin Search"> | <img src="public/image/edit_admin.png" width="120" alt="Edit Admin"> |


---


## Installation & Setup

1. Clone or download the project:
   ```
   git clone <PROJECT_URL>
   Navigate to the project folder and run PHP's built-in server:
   php -S localhost:8000
   
Open your browser and visit:

``http://localhost:8000/public/login.php ``

## Database connection settings are in these files:

database.php
delete.php
select.php
table.php
edit.php
profile_login.php

Default configuration:
```
$localhost = "localhost";
$username = "root";
$password = "";
$dbname = "System_Users";
```

Enter your password in the database password section, and the recommended software is MySQL Workbench.

## Admin Login

- To access the admin panel, the admin must first register.

  - Two sample admin users (for testing):
```
 Username: mmdmoradi

Username: saramoradi
```
-- Password: whatever is set during registration

-- After registration, admin can log in and manage users.


## Project Features

- User registration and login
- Profile management
- User information editing
- Email-based search for admins
- Automatic database and table creation
- Secure database operations using **PDO**
