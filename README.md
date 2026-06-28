# Assignment I - CTE & SQL Window Functions Project

## Course Details
* **Course Title:** Database Programming (C11665 - DPR400210)
* **Instructor:** Eric Maniraguha
* **Institution:** University of Lay Adventists of Kigali (UNILAK)

## 1. Business Problem & Scenario
This project implements a **Sales Management System** designed to track employees, product sales, and transactions. The main business problem addressed is evaluating employee sales performances, understanding organizational structure hierarchies, and analyzing revenue metrics for optimized management.

## 2. Database Schema & Structure
The relational database consists of 3 related tables:
* **Employees**: Contains `EmployeeID` (PK), `EmployeeName`, and `ManagerID` (Self-referencing Foreign Key).
* **Products**: Contains `ProductID` (PK), `ProductName`, `Category`, and `Price`.
* **Sales**: Contains `SaleID` (PK), `EmployeeID` (FK), `ProductID` (FK), `SaleDate`, `Quantity`, and `TotalAmount`.

---

## 3. Analysis and Findings (Three Levels of Insights)

### A. Descriptive Analysis (What happened?)
* Total high-value orders above $2,000 were completed by Alice Uwase and Bob Mugisha.
* The product catalog spans multiple categories including Electronics and Furniture.
* Alice Uwase achieved the highest transaction value of $2,400 on a Laptop order.

### B. Diagnostic Analysis (Why did it happen?)
* Alice Uwase and Bob Mugisha generated higher transaction values because they actively closed sales on premium high-ticket items like Laptops and Smartphones.
* The internal hierarchy shows that Ibrahim Ahmed oversees Eric Maniraguha, who drives the operational execution of the sales force, establishing clear management accountability.

### C. Prescriptive Analysis (What actions should be taken?)
* **Inventory Optimization**: Restock high-demand items (Laptops and Smartphones) since they account for the largest revenue chunks.
* **Employee Incentives**: Reward top performers based on the implemented dense ranking functions to boost company-wide morale.

---

## 4. Academic Integrity Statement
"I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged."
