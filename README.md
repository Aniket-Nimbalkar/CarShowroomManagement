# Car Showroom Management System

The **Car Showroom Management System** is a comprehensive application designed in **C# .NET** to facilitate efficient management of car showrooms. This system streamlines various aspects of showroom operations, such as car inventory tracking, customer management, sales processing, and reporting. With its user-friendly interface, developed using Windows Forms, the system provides an effective solution for managing the daily activities of a car dealership.

---

## Features of the Car Showroom Management System

### User Management
- Role-based login for **Admin** and **Sales Staff**.
- Secure authentication system with password hashing.

### Car Inventory Management
- Add, update, and delete car details.
- Maintain car categories (e.g., Sedan, SUV, Hatchback).
- Track availability status of cars.

### Customer Management
- Record and manage customer details.
- View purchase history of customers.

### Sales Management
- Process car sales transactions.
- Generate and print detailed sales invoices.
- Apply discounts and offers during the sales process.

### Reporting and Analytics
- Generate daily, weekly, and monthly sales reports.
- Track top-selling car models.
- Analyze sales trends and revenue statistics.

### Additional Features
- **Test Drive Scheduling:** Manage customer requests for test drives.
- **Loan Assistance:** Provide customers with EMI calculation and loan assistance details.

---

## Objectives of the Project

### Streamline Showroom Operations
Automate key operations, such as car inventory updates, sales tracking, and customer management.

### Enhance Customer Experience
Offer a seamless experience for customers through efficient transaction processing and test drive scheduling.

### Enable Data-Driven Decisions
Provide insights into sales trends and inventory needs through detailed analytics and reporting.

---

## Technology Stack

- **Programming Language:** C#
- **Framework:** .NET Framework (Windows Forms for UI)
- **Database:** Microsoft SQL Server
- **Development Environment:** Visual Studio
- **Libraries and Tools:** ADO.NET for database interaction, RDLC or Crystal Reports for reporting

---

## Database Design

1. **Users Table:**
   - Columns: `UserID`, `Username`, `Password`, `Role`

2. **Cars Table:**
   - Columns: `CarID`, `ModelName`, `Category`, `Price`, `Availability`

3. **Customers Table:**
   - Columns: `CustomerID`, `Name`, `Contact`, `Email`, `Address`

4. **Sales Table:**
   - Columns: `SalesID`, `CarID`, `CustomerID`, `DateOfSale`, `TotalAmount`

5. **TestDrive Table:**
   - Columns: `TestDriveID`, `CarID`, `CustomerID`, `Date`, `Status`

6. **Reports Table:**
   - Columns: `ReportID`, `ReportType`, `GeneratedDate`







