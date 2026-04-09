# 📦 Inventory Management System

> **Micro-Project | Alliance University – Alliance College of Engineering and Design**  
> Course: Programming in Python

---

## 👥 Team Members

| # | Name |
|---|------|
| 1 | L. Navaneesh Reddy |
| 2 | Mohit |
| 3 | Chrysolite |
| 4 | Pavan R |
| 5 | Sai Sathwik |

---

## 📌 Project Description

This is a fully functional **Inventory Management System** built using **Python** and **SQLite**.  
It helps businesses track, manage, and control product stock efficiently.

The system demonstrates core software engineering concepts:
- CRUD operations (Create, Read, Update, Delete)
- Object-oriented programming
- Database integration (SQLite)
- Data validation and error handling
- Business logic (alerts, reports, CSV export)

---

## ⚙️ Features

| Feature | Description |
|---------|-------------|
| ➕ Add Item | Add new products with full details |
| 👁️ View All | Display all inventory in a formatted table |
| 🔍 Search | Search by Item ID or Name |
| ✏️ Update | Modify any item's details |
| 🗑️ Delete | Remove items with confirmation prompt |
| ⚠️ Low Stock Alert | Flags items below minimum stock level |
| 💰 Stock Valuation | Calculates total inventory monetary value |
| 📊 Category Summary | Category-wise item count and value |
| 📁 Export CSV | Save inventory data to a spreadsheet file |

---

## 🛠️ Technologies Used

- **Python 3** – Core programming language
- **SQLite3** – Lightweight database (built into Python, no install needed)
- **CSV module** – For exporting reports

---

## 📁 Project Structure

```
inventory-management-system/
│
├── programs/
│   └── inventory.py       ← Main application
│
├── inventory.db            ← Auto-created database (SQLite)
├── inventory_export.csv    ← Generated when you export
└── README.md
```

---

## ▶️ How to Run

**Requirements:** Python 3.x (no extra libraries needed)

```bash
# Navigate to the project folder
cd inventory-management-system

# Run the program
python programs/inventory.py
```

The database is **created automatically** on first run with 5 sample items.

---

## 🎬 Demo Flow (for presentation)

```
1. Run the program
2. Choose Option 2 → View all items (pre-loaded sample data)
3. Choose Option 1 → Add a new item
4. Choose Option 6 → See Low Stock Alerts (some items pre-set to trigger)
5. Choose Option 7 → See total inventory value
6. Choose Option 9 → Export to CSV
```

---

## 🏪 Real-World Applications

- Retail shops and supermarkets
- Warehouses and manufacturing units
- Pharmacies and hospitals
- E-commerce platforms (Amazon, Flipkart)

---

## 🎯 Conclusion

This project demonstrates how Python can be used to solve real-world business problems.  
It implements CRUD operations, SQLite database integration, business logic (alerts, valuation), and report generation — mirroring features found in commercial ERP systems like SAP and Tally.

