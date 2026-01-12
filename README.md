# 📦 Mufaddal Traders Management System

**A comprehensive Windows Forms Application for managing trading operations.**

> **Mufaddal Traders** is a robust desktop application designed to streamline the entire trading process. It manages inventory, sales, shipping, and accounting through role-based access for Storekeepers, Shipping Managers, Marketing & Sales, Accountants, and IT Admins.

---

## 📸 Application Showcase

### 🔐 Secure Access
Role-based authentication ensures users only access what they need.

| **Login Screen** |
|:---:|
| <img width="500" alt="Secure Login Interface" src="https://github.com/user-attachments/assets/2f9c0971-3e3c-463f-9f23-fca421f0878d" /> |
| *Secure login for all departments* |

---

### 🏢 Department Dashboards
Tailored interfaces for each operational role.

| **Storekeeper** | **Shipping Manager** | **Marketing & Sales** | **Accountant** | **IT Admin** |
|:---:|:---:|:---:|:---:|:---:|
| <img width="180" alt="Storekeeper Dashboard" src="https://github.com/user-attachments/assets/e925b628-91ed-4c7f-ad88-ecb8ea0dec38" /> | <img width="180" alt="Shipping Manager Dashboard" src="https://github.com/user-attachments/assets/a9917c7c-4304-4956-acbe-990833ec5ac9" /> | <img width="180" alt="Marketing and Sales Dashboard" src="https://github.com/user-attachments/assets/e0ecfe22-d032-4b60-82ea-a6209a62c337" /> | <img width="180" alt="Accountant Dashboard" src="https://github.com/user-attachments/assets/1daee0ae-6ea0-4970-a7fd-370026867e9d" /> | <img width="180" alt="IT Admin Dashboard" src="https://github.com/user-attachments/assets/63f25a72-217b-4a6b-b883-8f68ddd8c382" /> |

---

### 📦 Inventory & Operations
Tools for managing stock and logistics.

| **Item Management** | **Stock Balance** |
|:---:|:---:|
| <img width="400" alt="Inventory Item Management" src="https://github.com/user-attachments/assets/c5aed511-2f75-40a9-825e-8230a8d0d827" /> | <img width="400" alt="Real-time Stock Balance" src="https://github.com/user-attachments/assets/d5da8233-4128-4e06-b5c4-3608df08f02b" /> |
| *Add, Update, and Delete Inventory Items* | *Real-time view of current stock levels* |

| **Purchase Orders** | **Reporting** |
|:---:|:---:|
| <img width="400" alt="Purchase Order Processing" src="https://github.com/user-attachments/assets/63430cd4-0095-49b8-9250-fd4aeacf8016" /> | <img width="400" alt="Crystal Report - Goods Issue Note" src="https://github.com/user-attachments/assets/4d04d3f8-7a29-4f1b-8450-2bc9fcc6c10e" /> |
| *Manage incoming orders from suppliers* | *Detailed Crystal Reports for Goods Issue Notes* |

---

## 🚀 Key Features

### 👤 Role-Based Modules
* **Storekeeper:** Manage stock, Goods Received Notes (GRN), Goods Issue Notes (GIN), and stock damage.
* **Shipping Manager:** Handle shipments, delivery orders, and logistics tracking.
* **Marketing & Sales (MSD):** Manage customer orders and sales operations.
* **Accountant:** Oversee payment vouchers, invoices, and financial records.
* **IT Admin:** Manage user accounts, system settings, and overall maintenance.

### 📊 Reporting & Analytics
* **Crystal Reports Integration:** Generate professional reports for invoices, GINs, GRNs, and stock status.
* **Real-time Data:** Instant updates on stock levels and order statuses across all departments.

### 🛠 Tech Stack

* **Language:** C# (.NET Framework)
* **GUI Framework:** Windows Forms (WinForms)
* **Database:** SQL Server
* **Reporting:** SAP Crystal Reports
* **Tools:** Visual Studio

---

## 📂 Project Structure

The project follows a standard Windows Forms application structure:

* `Mufaddal Traders` - Main project folder.
  * `frmLogin.cs` - Entry point authentication form.
  * `frmStorekeeperMenu.cs`, `frmShippingManagerMenu.cs`, etc. - Dashboard forms for each role.
  * `frmItems.cs`, `frmAddUpdateItems.cs` - CRUD operations for inventory.
  * `CrystalReport1.rpt` - Crystal Report definitions.
  * `App.config` - Database connection strings and configuration.
