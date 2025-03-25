# 🚀 Project Name

## 📌 Description
This project aims to develop a simple Database Management System (DBMS) using Bash shell scripting, allowing users to store and retrieve data from a hard disk. The system will operate through a command-line interface (CLI) menu, providing various options for managing databases and tables.

## 🔧 Prerequisites
Ensure you have the following installed:
- 🖥️ Bash (Unix/Linux environment)

## 📥 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AdhamBasheir/ITI-Database-Bash
   cd project
   ```
2. Set executable permissions for scripts:
   ```bash
   chmod +x *.sh
   ```

## 📌 Project Features

### 📖 Table of Contents
- [🔑 Authentication Menu](#-authentication-menu)
- [🏠 Main Menu](#-main-menu)
- [📂 Database Menu](#-database-menu)
- [📋 Table Menu](#-table-menu)
- [📝 CRUD Menu](#-crud-menu)


#### 🔹 **Authentication Menu**
Before accessing the database management system, users must authenticate or register. The authentication menu provides the following options:

- 🔑 **Login** - Allows users to log in using their credentials.
- 📝 **Register** - Enables new users to create an account.
- 👤 **Enter as Guest** - Provides limited access without authentication.
- ❌ **Exit** - Exits the application.

#### 🔹 **Main Menu**
After authentication, users are presented with the main menu:

- 🗄️ **DBMS** - Navigate to the database management system.
- 👥 **Groups** - (Feature placeholder for managing user groups).
- 🔄 **Logout** - Logs out the current user.
- ❌ **Exit** - Closes the application.

#### 🔹 **Database Menu**
Users can manage databases with the following operations:

- 📁 **Create Database** - Allows users to create a new database.
- 📂 **Select Database** - Enables users to work with an existing database.
- ✏️ **Rename Database** - Changes the name of an existing database.
- 🗑️ **Delete Database** - Removes an existing database permanently.
- 📜 **View Databases** - Lists all available databases.
- 🔄 **Logout** - Logs out the current user.
- 🚪 **Exit BDMS** - Closes the application.

#### 🔹 **Table Menu**
Once a database is selected, users can manage tables:

- ➕ **Create Table** - Defines a new table within the database.
- 📋 **Select Table** - Opens a table to perform CRUD operations.
- ✏️ **Rename Table** - Changes the name of an existing table.
- 🗑️ **Delete Table** - Removes a table from the database.
- 📜 **View Tables** - Lists all tables within the selected database.
- 🔙 **Return to Main Menu** - Returns to the main database menu.

#### 🔹 **CRUD Menu (Table Operations)**
After selecting a table, users can perform record-level operations:

- 📝 **Insert Record** - Adds new data into the table.
- ❌ **Delete Record** - Removes a specific record based on conditions.
- 🔄 **Update Record** - Modifies an existing record in the table.
- 🔍 **Select Record** - Searches for specific records within the table.
- 📊 **Show All Records** - Displays all records in the table.
- 🚪 **Exit** - Returns to the table menu.

---

🚀 **Enjoy managing your databases efficiently!** 🎯

## 🚀 Usage
Run the main script:
```bash
./main.sh
```
For specific operations:
```bash
./auth.sh        # 🔐 Authentication operations
./crud.sh        # 📝 CRUD operations
./menu.sh        # 📋 Menu handling
```



