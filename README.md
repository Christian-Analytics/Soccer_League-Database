# Soccer League Database Project ⚽

Welcome to the Soccer League Database Repository! This project features a robust database system designed to efficiently organize and manage team and match data for soccer leagues. It includes detailed documentation of the database schema and example queries to interact with the data. This project highlights my expertise in database design, SQL, and data management within a sports context, ensuring that team and match information is always well-organized and accessible.

## Getting Started 🚀

### Prerequisites 🔧
- **[SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)**: Install SQL Server to load the master and log data files.
- **SQL Server Management Studio (SSMS)**: Use SSMS for database management.

### Installation 📥
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Christian-Analytics/soccer_league-database.git
    cd soccer_league-database
    ```

2. **Attach the Database**:
    - Open SSMS and connect to your SQL Server.
    - Right-click "Databases" and choose "Attach...".
    - Click "Add..." and select `Soccer League.mdf` from the `MDF_and_LDF` folder.
    - Verify the path for `Soccer League_Log.ldf` or locate it manually.
    - Click "OK".

### Documentation 📚
- **Database Design Documentation**: Find detailed descriptions of the tables and relationships within the database with a narrative provided, relational schema, a data dictionary and more in the `DBDD` folder.

## Database Structure 🏗️
- **Data File**: Includes 18 base tables, 5 views, and 15 stored procedures for common operations.
    - Views and stored procedures are organized in respective folders in SSMS.

## Features 🌟
- **Database Schema**: Structured tables for players, coaches, teams, sponsors, fields, vendors, referees and matches.
- **Query Collection**: Demonstrates SQL capabilities for data manipulation and reporting.
- **Data Examples**: Pre-loaded datasets facilitate easy testing.
