![Screenshot 2024-11-22 151211](https://github.com/user-attachments/assets/24f3bf69-5383-4321-b584-5670b8ce4809)

# One Zamboanga: An Evacuation Management System for Zamboanga City Setup Guide

This README provides step-by-step instructions on how to set up, configure, and run the system locally using **XAMPP**.

---

## 📦 Required Software

Make sure you have the following installed:

- [XAMPP](https://www.apachefriends.org/index.html) – for Apache, PHP, and MySQL
- Code editor (e.g., [Visual Studio Code](https://code.visualstudio.com/))
- Web browser (e.g., Chrome, Firefox)
- Install or download the Zip File of the repo or project oneZamboanga_capstone
---

## ⚙️ Setup Instructions

### 1. Start Apache and MySQL in XAMPP

1. Open the **XAMPP Control Panel**
2. Click **Start** next to **Apache**
3. Click **Start** next to **MySQL**

Both services should turn green when running successfully.

---

### 2. Place the Project Folder in `htdocs`

1. Locate your XAMPP installation directory (usually `C:\xampp`)
2. Open the `htdocs` folder:  
   `C:\xampp\htdocs`
3. Copy and paste the oneZamboanga_capstone project folder into `htdocs`


---

### 3. Set Up the Database

1. Open your browser and go to: http://localhost/phpmyadmin

2. Click on **New** in the left sidebar to create a new database  
Enter the database name "one_zambo" and click **Create**

3. Import the SQL file:
- Select new database
- Click the **Import** tab
- Choose the SQL file located in oneZamboanga_capstone/database/one_zamboanga.sql
- Click **Go**

---

### 4. To Run the Project Locally

Make sure to start both Apache and MySQL then open your browser and go to: http://localhost/oneZamboanga_capstone

To login use these accounts:
Superadmin
- username: superadmin
- password: 123

Barangay Admin
- username: admin
- password: 123

Community worker
- username: worker
- password: 123

