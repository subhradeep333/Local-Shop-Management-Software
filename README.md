# 🏪 Shop Management Software

<p align="center">

![Python](https://img.shields.io/badge/Python-3.14-blue?style=for-the-badge\&logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge\&logo=mysql)
![CLI](https://img.shields.io/badge/Interface-Command%20Line-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

A **CLI-based Shop Management Software** built using **Python** and **MySQL**. The application helps retail shops efficiently manage products, customers, inventory, sales, and reports through a simple and user-friendly command-line interface. It follows a modular architecture, making it easy to maintain, extend, and upgrade to a graphical user interface (GUI) in the future.

---

# 📖 Table of Contents

* Overview
* Features
* Technology Stack
* Project Structure
* Database Design
* Installation
* Usage
* Future Enhancements
* Learning Outcomes
* Contributing
* License
* Author

---

# 📌 Overview

Managing a retail shop manually can be time-consuming and error-prone. This software automates daily business operations such as product management, customer management, inventory tracking, sales processing, and report generation.

The project is designed with a modular structure, allowing each feature to be maintained independently while making future upgrades easier.

---

# ✨ Features

## 🔐 Authentication

* Secure Admin Login
* Password Protected Access

---

## 📦 Product Management

* Add Products
* Update Products
* Delete Products
* View Products
* Search Products

---

## 👥 Customer Management

* Add Customers
* View Customer Details
* Search Customers
* Customer Purchase History

---

## 💰 Sales Management

* Generate Bills
* Automatic Total Calculation
* Store Sales Records
* Update Inventory Automatically

---

## 📦 Inventory Management

* Track Product Stock
* Low Stock Alerts
* Restock Products

---

## 📊 Reports

* Daily Sales Report
* Overall Sales Report
* Product-wise Sales
* Inventory Report

---

# 🛠 Technology Stack

| Technology             | Purpose               |
| ---------------------- | --------------------- |
| Python                 | Backend Development   |
| MySQL                  | Database Management   |
| mysql-connector-python | Database Connectivity |
| CLI                    | User Interface        |

---

# 📂 Project Structure

```text
Shop-Management-Software/
│
├── .gitignore
├── README.md
├── LICENSE
├── requirements.txt
├── main.py
│
├── config/
│   └── config.py
│
├── database/
│   ├── __init__.py
│   ├── db_connection.py
│   └── schema.sql
│
├── modules/
│   ├── __init__.py
│   ├── auth.py
│   ├── product.py
│   ├── customer.py
│   ├── sales.py
│   ├── inventory.py
│   └── reports.py
│
├── utils/
│   ├── menu.py
│   ├── validation.py
│   ├── helper.py
│   └── bill.py
│
├── data/
│   └── invoices/
│
└── screenshots/
```

---

# 🗄 Database Design

The project uses a relational MySQL database with the following tables:

* Admin
* Products
* Customers
* Sales
* Sales_Items

---

# ⚙ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/subhradeep333/Shop-Management-Software.git
```

---

## 2. Navigate to the Project Folder

```bash
cd Shop-Management-Software
```

---

## 3. Create a Virtual Environment

### Windows

```bash
python -m venv .venv
```

### macOS / Linux

```bash
python3 -m venv .venv
```

---

## 4. Activate the Virtual Environment

### Windows

```bash
.venv\Scripts\activate
```

### macOS / Linux

```bash
source .venv/bin/activate
```

---

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6. Create the Database

```sql
CREATE DATABASE shop_management;
```

Import the schema:

```bash
mysql -u root -p shop_management < database/schema.sql
```

---

## 7. Configure the Database

Update the database credentials inside:

```text
database/db_connection.py
```

```python
HOST = "localhost"
USER = "root"
PASSWORD = "your_password"
DATABASE = "shop_management"
```

---

## 8. Run the Application

```bash
python main.py
```

---

# 💻 Sample Menu

```text
=====================================
      SHOP MANAGEMENT SOFTWARE
=====================================

1. Product Management
2. Customer Management
3. Sales Management
4. Inventory Management
5. Reports
6. Exit

Enter Your Choice:
```

---

# 📷 Screenshots

```text
screenshots/
│
├── login.png
├── dashboard.png
├── products.png
├── sales.png
└── reports.png
```

> Add screenshots after completing the project.

---

# 🚀 Future Enhancements

* Tkinter GUI
* Barcode Scanner Integration
* QR Code Billing
* GST Invoice Generation
* PDF Invoice Export
* Supplier Management
* Dashboard Analytics
* Multi-user Authentication
* Email Invoice Support
* Cloud Database Integration

---

# 🎯 Learning Outcomes

This project helped me gain practical experience in:

* Python Programming
* Object-Oriented Programming (OOP)
* MySQL Database Design
* CRUD Operations
* SQL Queries
* Database Connectivity
* Modular Programming
* Exception Handling
* Inventory Management
* Command-Line Application Development

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## **Subhradeep Roy Chowdhury**

**BCA Student | Python Developer | Java Enthusiast**

🔗 **GitHub:** https://github.com/subhradeep333

🔗 **LinkedIn:** https://www.linkedin.com/in/subhradeep333

---

<p align="center">

⭐ **If you found this project useful, consider giving it a Star!**

</p>
