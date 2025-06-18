# 🚗 TorqueTrack – Concept Document
## 📌 Overview
TorqueTrack is a full-stack, local-network accessible application designed to replicate and simplify core features of Mitchell 1, the software used in auto repair shops. It will provide a lightweight, modern solution for managing customers, vehicles, repair orders, and payments, while generating printable documents like estimates and invoices.

## 🧑‍🔧 Purpose
### Auto repair shops often rely on bulky or outdated commercial systems. TorqueTrack is intended to:
- Provide essential shop management tools
- Be locally hosted and usable without internet
- Offer a clean, user-friendly interface for multi-user access on the same network

## 🎯 Goals
- Create a fully functional CRUD application for core shop data
- Support generating and printing shop documents in PDF format
- Deliver a desktop-friendly Java GUI to start and manage the backend server
- Ensure access for multiple users on the same Wi-Fi network (LAN)

## 🔧 Key Features (MVP)
### Customer Management
Add, view, update, and delete customer profiles

### Vehicle Records
Associate vehicles with customers; store make, model, year, etc.

### Repair Orders
Create and manage repair orders tied to vehicles and customers

### Payments
Track payment status, type, and amount for each order

### PDF Export
Generate estimates, invoices, and work orders using a JS PDF library

### GUI-Based Backend
JavaFX GUI to start/stop the Spring Boot server with IP display and logs

### Local Network Access
Server accessible by shop computers on the same Wi-Fi network

## 🚫 Out of Scope (for now)
- Parts inventory management
- Online/cloud access
- Scheduling or calendar tools
- VIN decoding or third-party API integrations

## 🏗️ Tech Stack
**Backend:** Java (Spring Boot)

**Database:** PostgreSQL (or MySQL)

**Frontend:** Vanilla JS or React

**PDF Generation:** jsPDF or PDFMake

**GUI:** JavaFX

**Network Access:** Localhost IP with LAN availability

## 📈 Future Enhancements (Post-MVP)
- User authentication and roles
- Search and filtering
- VIN decoder integration
- Parts ordering system
- Advanced analytics and reports

