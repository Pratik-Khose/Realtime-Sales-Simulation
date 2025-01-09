# Bakery Sales Simulation and Real-Time Analytics

This project demonstrates how to create a sales simulation for a bakery business using SQL Server and display its real-time sales information in Power BI Desktop. The tutorial guides you through setting up the database, generating sales data, and visualizing the results using the Direct Query connection.


https://github.com/user-attachments/assets/8be8337f-1684-4aec-b1c0-9ad40e9c49dc


## Features

- **SQL Server Setup**: Create and manage a database for bakery sales.
- **Automated Sales Generation**: Use SQL queries to simulate real-time sales.
- **Power BI Integration**: Link the database to Power BI using the Direct Query method.
- **Real-Time Dashboard**: Visualize sales information dynamically using Power BI dashboards.
- **Relational Modeling**: Establish relationships between tables to enable meaningful insights.

## Project Overview

This project includes the following steps:

1. **Database Creation**
    - Create a SQL Server database named `Star Bakery`.
    - Add tables to store product, salesperson, order type, and order data.

2. **Data Population**
    - Populate the tables with initial data using SQL queries.
    - Implement a SQL script to generate sales data automatically.

3. **Power BI Integration**
    - Connect the SQL Server database to Power BI using Direct Query.
    - Build a relational model in Power BI to link tables.

4. **Dashboard Creation**
    - Design a Power BI dashboard to visualize real-time sales data.

5. **Simulation Execution**
    - Run the SQL-based simulation and observe live updates in Power BI.

## Prerequisites

To run this project, you need the following tools installed:

- SQL Server Management Studio (SSMS)
- Power BI Desktop

## Installation and Setup

### SQL Server Setup
1. Open SQL Server Management Studio.
2. Create a new database named `Star Bakery`.
3. Run the provided SQL scripts to create and populate the following tables:
    - `Product`: Stores product information (ID, title, price).
    - `Sales Person`: Stores salesperson details (first name, last name).
    - `Order Type`: Stores order types (ID, order type).
    - `Orders`: Records customer orders (ID, date, product ID, salesperson ID, order type ID, etc.).

4. Execute the SQL script to generate sales data automatically.

### Power BI Setup
1. Open Power BI Desktop.
2. Connect to the SQL Server database using the Direct Query connection method.
3. Build a relational model by linking tables.
4. Create a dashboard to display real-time sales information.

### Running the Simulation
1. Start the SQL script to simulate sales generation.
2. Refresh the Power BI dashboard to view real-time updates.

## Files Included


- `power_bi.pbix`: Power BI file with the dashboard setup.

## Screenshots
![Screenshot 2025-01-09 081532](https://github.com/user-attachments/assets/21080042-dce1-48e8-8bb6-43f77bdd5999)

### Dashboard Example
![Screenshot 2025-01-09 101501](https://github.com/user-attachments/assets/7eeca086-b123-44f1-b2b3-8b36fbfb4b7c)


## Usage

1. Clone this repository to your local machine.
2. Follow the setup instructions to configure the SQL Server database and Power BI dashboard.
3. Run the simulation and observe real-time updates in the Power BI dashboard.

## Contributing

If you have suggestions or improvements, feel free to open a pull request or submit an issue.


## Contact

For questions or feedback, feel free to reach out:

- **Email**: pratikkhose13@gmail.com
- **GitHub**: [Pratik-Khose](https://github.com/Pratik-Khose)

---
