# 🍽️ SMAIT Restaurant Management System

> **Terminal-based restaurant operations platform** — Complete CLI system built with pure Dart

A comprehensive command-line restaurant management solution handling menu operations, table bookings, inventory tracking, billing, and multi-branch coordination.

---

## 📊 System Flow

<p align="center">
  <img src="https://github.com/user-attachments/assets/91d91efe-e2f1-4df6-a545-676280c654b8" alt="System Flow Diagram" width="800"/>
</p>

---

## 👥 Team Members

| Name            | GitHub |
|-----------------|--------|
| **Deephang Thegim** | [@mrdeephang](https://github.com/mrdeephang) |
| **Pradip KC** | |

---

## 🎯 Overview

A complete CLI system for managing restaurant operations including:

- 📋 **Menu management** — CRUD operations for food items
- 🪑 **Table booking & orders** — Reservation and order tracking
- 📦 **Inventory tracking** — Multi-branch stock management
- 💰 **Billing & reporting** — Sales reports and financial summaries
- 🔐 **Role-based access control** — Admin, Cashier, and Waiter roles

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Language** | Pure Dart |
| **Storage** | JSON files + CSV |
| **Dependencies** | None (no external packages) |
| **IDE** | Visual Studio Code |

---

## 📁 File Structure

```
restaurant_system/
├── main.dart                    # Main entry point
│
├── models/                      # Data structures
│   ├── user.dart
│   ├── menu_item.dart
│   ├── table.dart
│   ├── order.dart
│   └── attendance.dart
│
├── services/                    # Business logic
│   ├── auth_service.dart
│   ├── menu_service.dart
│   ├── table_service.dart
│   ├── order_service.dart
│   ├── billing_service.dart
│   ├── inventory_service.dart
│   ├── report_service.dart
│   ├── transfer_service.dart
│   ├── branch_service.dart
│   └── attendance_service.dart
│
├── utils/                       # Helper functions
│   └── file_handler.dart
│
└── data/                        # JSON database
    ├── attendance/
    │   └── attendance.csv
    ├── users.json
    ├── menu.json
    ├── tables.json
    ├── inventory.json
    ├── staffs.json
    ├── invoices/
    │   └── sales_report.csv
    ├── branches/
    │   ├── frankfurt.json
    │   ├── lisbon.json
    │   ├── noida.json
    │   ├── oslo.json
    │   └── pokhara.json
    └── transfers/               # Transfer reports
```

---

## 👔 User Roles

| Role | Permissions |
|------|-------------|
| **Admin** | Full system control, all operations |
| **Cashier** | Process bills, view orders, inventory access |
| **Waiter** | Take orders, manage tables, view menu |

---

## ✨ Features

### ⏰ Attendance Management
- Check-in/check-out for all staff members
- Supports managers, waiters, cashiers, and other staff
- CSV-based attendance tracking

### 🍴 Menu Management
- Add/update/delete menu items
- Category organization (Appetizers, Mains, Desserts, etc.)
- Toggle item availability status
- Price management

### 🪑 Table Operations
- Book and free tables
- Real-time occupancy tracking
- Order assignment per table
- Table status monitoring

### 📝 Order Processing
- Add/remove items from orders
- Modify item quantities
- Automatic total calculation
- Order history tracking

### 📦 Inventory Management
- Multi-branch inventory control
- Add/remove items across branches
- View stock levels by location
- Quantity adjustments
- Inter-branch transfer handling

### 📊 Reporting & Analytics
- Daily sales reports (TXT + CSV formats)
- Inventory status summaries
- Financial reports
- Branch-wise performance metrics

---

## 🚀 Setup & Installation

### Prerequisites
- Dart SDK installed on your system

### Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/mrdeephang/RestaurantManagementSystem.git
cd RestaurantManagementSystem

# 2. Run the system
dart run main.dart
```

**Note:** Ensure you're in the correct directory before running.

---

## 🏢 Supported Branches

The system currently manages inventory and operations for:
- 🇩🇪 Frankfurt
- 🇵🇹 Lisbon
- 🇮🇳 Noida
- 🇳🇴 Oslo
- 🇳🇵 Pokhara

---

## 🔮 Future Enhancements

- 📱 **GUI version** — Desktop or web interface
- 🌐 **API integration** — RESTful backend support
- 📧 **Email notifications** — Order and inventory alerts
- 📈 **Advanced analytics** — Graphical reports and insights
- 🔄 **Real-time sync** — Cloud database integration

---

## 📄 License

Copyright © 2025. All rights reserved.

