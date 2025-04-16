# Inventory Management System

This project is a **Java EE-based web application** designed to manage inventory efficiently. It provides features to add, update, delete, and view inventory items. This repository includes a deployable `.war` file and a MySQL database schema for setup.

## 🚀 Features

- Add, update, and delete inventory items
- Simple and intuitive web interface
- MySQL database integration

## 🧰 Technologies Used

- **Java EE / JSP / Servlets**
- **MySQL**
- **Apache Tomcat (for deployment)**
- HTML, CSS, JavaScript (frontend)
- JDBC for database connectivity

## 📂 Project Structure

- `InventoryWeb.war` - Deployable WAR file for Apache Tomcat.
- `springinventoryweb.sql` - SQL file for MySQL database schema and initial data.

## 🔧 Installation and Setup

### Prerequisites

- Java JDK 8 or higher
- Apache Tomcat 8.5+
- MySQL 5.7+
- A database GUI like MySQL Workbench (optional)

### Steps

1. **Clone this repository:**

    ```bash
    git clone https://github.com/Sanikapatil21/inventory-management-system.git
    ```

2. **Import the database:**

    - Open MySQL Workbench or your preferred tool.
    - Run the `springinventoryweb.sql` script to create the database and required tables.

3. **Configure Database Connection:**

    - Locate the database connection configuration file (e.g., `DBConnection.java`, `context.xml`, or `web.xml`).
    - Update the DB URL, username, and password according to your local MySQL setup.

4. **Deploy the WAR file:**

    - Copy `InventoryWeb.war` to the `webapps` folder of your Apache Tomcat installation.
    - Start Tomcat and access the app at:  
      [http://localhost:8080/InventoryWeb](http://localhost:8080/InventoryWeb)

## 👤 User Roles

- **Admin/User:** Can manage all inventory items.

## 🛠️ Future Improvements

- Authentication and user role management
- Inventory alerts and notifications
- REST API for external integration
- Enhanced UI with modern JS frameworks (e.g., React or Angular)

## 📝 License

This project is licensed under the MIT License.
