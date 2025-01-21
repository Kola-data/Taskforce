# Taskforce 

**URL for hosted project**: kwola.pythonanywhere.com

**Authentication** : Username = admin
                   : Password = 123


# Taskforce: Wallet Web Application

## Introduction

**Use Case:** 

A simple and intuitive wallet web application designed to help users manage their finances effectively. With Taskforce, users can track transactions, generate reports, set budgets, and visualize spending in an organized manner and out.

---

## Features  

- **Transaction Tracking:** Monitor all incoming and outgoing transactions from multiple accounts.  
- **Report Generation:** Create detailed reports for any desired time period.  
- **Budget Management:** Set a spending limit and receive notifications if the budget is exceeded.  
- **Category Management:** Add categories and subcategories to organize expenses.  
- **Expense Linking:** Link transactions with relevant categories or subcategories for better tracking.  
- **Data Visualization:** View a summary of transactions with charts and graphs.  

---

## Installation  

This project is built using **Flask** and **MySQL**. Follow the instructions below to set up the application:  

### Prerequisites  
Ensure you have the following installed on your system:  
- Python (3.8 or later)  
- MySQL Server  
- Git  

### Windows  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/Kola-data/Taskforce.git  
   cd Taskforce

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv  
   venv\Scripts\activate

3. Install the required dependencies:
      ```bash
      pip install -r requirements.txt
  
  
4. Open MySQL and create a database:
      ```bash
      CREATE DATABASE finance_tracker;
  
5. Import database in :
  
      /db/finance_tracker.sql or
  
6. Run the project :
      ```bash
      flask run  



Open your browser and navigate to http://127.0.0.1:5000.


**Usage**

After installation, you can:

Create payment methods (e.g., bank account, mobile money).
Add transactions and categorize them.
Generate reports for any desired time period.
Visualize your expenses and income in graphical form.
Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements or bug fixes.

License
This project is licensed under the MIT License.
   

**Installation Guide for macOS and Linux**

**Prerequisites**

Ensure the following are installed on your system:


Python (Version 3.8 or later)
MySQL Server
Git
pip (Python package manager)


1. Clone the Repository and open a terminal:
      ```bash
      git clone https://github.com/Kola-data/Taskforce.git
      cd Taskforce
  
2. Create a Virtual Environment and Activate:
      ```bash
      python3 -m venv venv
      source venv/bin/activate
  
3. Install Project Dependencies
      ```bash
      pip install -r requirements.txt
  
4. Install MySQL Server macOS Use Homebrew to install MySQL and Start the MySQL service:
      ```bash
      brew install mysql
      brew services start mysql
  
5. Linux Installation. Use your package manager to install MySQL:
      ```bash
      sudo apt update
      sudo apt install mysql-server

6. Secure the MySQL installation (optional but recommended) Start the MySQL service:
      ```bash
      sudo mysql_secure_installation
    
      sudo systemctl start mysql
  
7. Set Up the Database and Log into the MySQL server:
      ```bash
      mysql -u root -p

Enter your MySQL root password when prompted.

8. Create the database:
      ```bash
      CREATE DATABASE taskforce;
      Exit MySQL:

  
9. Start the Application (Start the Flask development server):
      ```bash
      flask run

10. Open your browser and navigate to:
      ```bash
      http://127.0.0.1:5000


**Troubleshooting**


If MySQL isn’t recognized, ensure its binary is added to your PATH.
For permission issues, try running commands with sudo if necessary.
Verify Python version by running python3 --version to ensure compatibility.
Verify venv is well installed and all the dependancies

