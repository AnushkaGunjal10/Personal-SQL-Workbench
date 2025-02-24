# SQL Workbench GUI

A Python-based GUI application for interacting with a MySQL database using **Tkinter** and **MySQL Connector**.

## Features
- Connect to MySQL server
- View available databases
- View tables within a selected database
- Display table structure (column names, data types, constraints)
- Retrieve and display table data in a structured format

## Technologies Used
- **Python**: Core programming language
- **Tkinter**: GUI framework
- **MySQL Connector**: Database connectivity
- **Pandas**: Data handling (potentially for future enhancements)

## Installation

### Prerequisites
1. Install **Python 3.x**
2. Install **MySQL Server**
3. Ensure MySQL is running and accessible with valid credentials.

### Install Required Libraries
Run the following command to install dependencies:

```sh
pip install mysql-connector-python pandas
```

## Usage

1. Run the script:
   ```sh
   python sql_workbench.py
   ```
2. Click **"Connect to MySQL"** to establish a database connection.
3. Use the provided buttons to:
   - View available databases.
   - Select a database and view its tables.
   - Select a table to view its structure.
   - Fetch and display table data.

## UI Design
- **Background Color:** `#3B6790`
- **Button Color:** `#EFB036`
- **Listbox & Textbox Background:** `#23486A`
- **Treeview Styling for Table Data Display**

## Notes
- Default MySQL credentials are `root` and `Welcome@2020`. Modify them if needed.
- Supports only **local MySQL connections**.
- **Limited to first 10 rows** when fetching table data.

## Future Enhancements
- Allow custom SQL queries
- Export table data to CSV
- User authentication for secure database connections

