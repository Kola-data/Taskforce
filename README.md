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


  2-1. In this case, the above commands did not work. go with this:

      mkdir venv
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


  
   


