# Hospital Management System

## Overview

The **Hospital Management System** is a comprehensive software solution developed in Java to streamline the management of hospital operations. The system is designed to handle various aspects of hospital administration, including managing doctors, patients, and the overall hospital management tasks.

## Features

### 1. **Doctor Management**
   - **Add/Edit/Delete Doctor Records**: Allows administrators to manage doctor profiles, including specialties, schedules, and personal details.
   - **View Doctor Schedules**: Patients and staff can view doctors' availability for consultations.
   - **Assign Patients to Doctors**: Doctors can be assigned to patients based on their specialization and availability.

### 2. **Patient Management**
   - **Patient Registration**: New patients can be registered into the system with their personal and medical details.
   - **Manage Patient Records**: The system keeps a detailed record of patient history, treatment plans, and prescriptions.
   - **Appointment Scheduling**: Patients can schedule, reschedule, or cancel appointments with doctors.
   - **Billing and Invoicing**: Generates bills for the treatments and services availed by patients.

### 3. **Hospital Management**
   - **Staff Management**: Admins can manage staff records, roles, and responsibilities within the hospital.
   - **Room Allocation**: Efficient allocation of rooms and beds to patients based on availability.
   - **Inventory Management**: Track hospital inventory, including medicines, equipment, and other supplies.
   - **Reporting**: Generate reports on hospital operations, doctor performance, and patient statistics.

## Technologies Used

- **Programming Language**: Java
- **Database**: MySQL (or any other preferred RDBMS)
- **Framework**: JavaFX/Swing (for GUI applications) or JSP/Servlets (for web-based applications)
- **IDE**: Eclipse/IntelliJ IDEA/NetBeans

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jindalayush326/Hospital-Management-System
   ```
2. **Import the Project into Your IDE**:
   - Open your preferred Java IDE (Eclipse, IntelliJ IDEA, or NetBeans).
   - Import the project as a Maven/Gradle/Java project.

3. **Database Setup**:
   - Create a MySQL database named `hospital_management`.
   - Run the SQL scripts provided in the `database` directory to create the necessary tables and relationships.
   - Update the `db.properties` file with your database credentials.

4. **Run the Application**:
   - Compile and run the `Main.java` file from your IDE.
   - For a web-based application, deploy it on a server like Apache Tomcat.

## Usage

### Doctor Module

- **Login**: Doctors can log in to access their dashboard.
- **Patient Consultations**: View and manage patient consultations.
- **Prescriptions**: Generate and manage patient prescriptions.

### Patient Module

- **Registration/Login**: Patients can register and log in to manage their profiles.
- **Book Appointments**: Schedule appointments with doctors based on availability.
- **View Medical Records**: Access past consultations and medical history.

### Management Module

- **Admin Dashboard**: Access to various administrative functions like managing doctors, patients, staff, and inventory.
- **Reports**: Generate and view detailed reports on hospital operations.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
