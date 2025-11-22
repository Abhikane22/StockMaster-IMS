# StockMaster IMS – Inventory Management System

StockMaster IMS is a MERN-based Inventory Management System designed to replace manual stock registers and Excel sheets. It centralizes inventory data, manages stock transactions, and provides real-time warehouse visibility. It supports operations including receiving stock, delivering orders, internal transfers, stock adjustments, and movement history tracking.

## Project Overview
The system aims to digitalize and optimize inventory flow inside warehouses. It provides actionable dashboards, modular functionality, and seamless tracking to improve accuracy and operational efficiency.

## Objective
To build a digital platform that simplifies end-to-end inventory handling with real-time visibility and error-free automated processing.

## Core Features

### Dashboard
- Total products count
- Pending receipts and deliveries
- Low stock alerts
- Internal transfer summary

### Product Management
- Add, edit, and view product details
- SKU, category, unit, and initial stock setup
- Stock allocation per warehouse location

### Incoming Goods (Receipts)
- Create a receipt from vendor & update stock
- Quantity validation
- Auto stock increment

### Delivery Orders (Outgoing Goods)
- Create delivery order for customer dispatch
- Validate packing and shipment
- Automatic stock deduction

### Internal Transfers
- Warehouse-to-warehouse / rack-to-rack movement
- Auto logging for traceability

### Stock Adjustments
- Physical vs recorded stock comparison
- Apply corrections and log reasons

### Movement History
- Complete audit trail of inventory movement

## Technology Stack

| Component | Technology |
|----------|-----------|
| Frontend | React.js, React Router DOM, Axios, React-Icons, Bootstrap |
| Backend | Node.js, Express.js |
| Database | MongoDB + Mongoose |
| Authentication (Upcoming) | JWT / Firebase |
| Version Control | Git & GitHub |

## Project Folder Structure
