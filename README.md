# Sydney Automotive Group (SAG) System

## 📌 Overview

This project is part of Database Management Systems . The objective is to develop a database-driven application for the Sydney Automotive Group (SAG) using Python (Flask framework) and PostgreSQL. The application allows authorized salespersons to manage car sale records via a web-based interface.

The system supports:
- Secure login functionality
- Viewing a summary of car sales
- Searching and filtering car sale records
- Adding new cars for sale
- Updating car sale records

## 📁 Project Structure


## ⚙️ Technologies Used

- **Python 3**
- **Flask**: For creating the web interface
- **psycopg2**: For PostgreSQL database connectivity
- **PostgreSQL**: Database management system

## 🚀 Getting Started

### 1. Clone the Repository

### 2. Install Dependencies
Install Flask and psycopg2:

### 3. Setup Database
- Make sure PostgreSQL is installed and running.
- Create a database for SAG.
- Run the SQL script to set up schema and sample data:

### 4. Configure `database.py`
- Ensure the connection string and credentials in `database.py` match your PostgreSQL setup.

### 5. Run the Application
Access the web interface via `http://127.0.0.1:5001/`

## 🔍 Key Functions

- **checkLogin(username, password)**: Validates login credentials.
- **getCarSalesSummary()**: Displays a summary of all car sales.
- **findCarSales(keyword)**: Searches for cars by keyword (make, model, buyer, or salesperson).
- **addCarSale(details)**: Adds a new car sale record.
- **updateCarSale(sale_id, update_info)**: Updates sale details (buyer, salesperson, sale date).

## ⚠️ Academic Integrity Notice

All work submitted must be your own. Use of generative AI tools (e.g., ChatGPT, Copilot) is strictly prohibited as per course policy. Violation will result in academic penalties.

## 👨‍👩‍👧‍👦 Group Members

- Name 1 (SID)
- Name 2 (SID)
- Name 3 (SID)


---

