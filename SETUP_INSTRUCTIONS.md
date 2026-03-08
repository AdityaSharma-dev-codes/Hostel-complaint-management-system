# Setup and Running Instructions

Follow these steps to set up and run the Hostel Complaint Management System on your local machine.

## 📋 Prerequisites

- **Java Development Kit (JDK)**: Version 11 or higher.
- **Apache Maven**: Installed and added to your system PATH.
- **MySQL Server**: Version 8.0 or higher.

## 🗄️ Database Configuration

1. **Initialize Database**: Execute the `hostel_complaint_db.sql` script on your MySQL server.
   ```bash
   mysql -u root -p < hostel_complaint_db.sql
   ```

2. **Update Credentials**: If your MySQL username or password differs from the defaults, update `src/main/java/com/hostel/util/DBConnection.java`:
   - `DB_URL`: `jdbc:mysql://localhost:3306/hostel_complaint_db`
   - `DB_USER`: `root`
   - `DB_PASSWORD`: `19232005` (or your password)

## 🚀 Building and Running

1. **Build Project**: Navigate to the project root and run:
   ```bash
   mvn clean install
   ```

2. **Launch Server**: Run the application using the embedded Tomcat plugin:
   ```bash
   mvn tomcat7:run
   ```

3. **Access Application**: Open your browser and go to:
   `http://localhost:8080/hostel-complaint-management`

## 👤 Sample Credentials

| Role | Email | Password |
| :--- | :--- | :--- |
| **Admin** | `admin@hostel.com` | `admin@123` |
| **Staff** | `john@hostel.com` | `john@123` |
| **Student** | `alice@student.com` | `alice@123` |

---
**Note**: Ensure port `8080` is available before running the server.
