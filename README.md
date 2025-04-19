# 🚌 Online Bus Booking System

## 🧾 Project Overview

The **Online Bus Booking System** is a comprehensive desktop application built using **Python** and **Tkinter**. It allows users to:
- Book bus tickets
- View booking history
- Offers admin functionalities to manage bus operators, routes, and schedules

It uses **SQLite** as its backend database for storing all records including bookings, routes, buses, and operators.

---

## 🚀 Key Features

### 👤 User Interface
- Interactive GUI built with Tkinter
- Responsive design suitable for various screen sizes
- Simple and intuitive navigation

### 🧳 Booking System
- Search buses by route and date
- Select from available buses
- Enter passenger details
- View fare calculation
- Generate booking confirmation

### 🛠️ Admin Functions
- Add, edit, or delete bus operators
- Manage bus details and types
- Configure routes and stations
- Set running schedules and manage seat availability

### 🗃️ Database Integration
- SQLite used for persistent storage
- Tables for operators, buses, routes, schedules, and bookings
- Built-in data validation and error handling

---

## 🧰 Prerequisites

Ensure you have the following installed:

- Python 3.x
- Tkinter (usually bundled with Python)
- SQLite3 (comes with Python)

---

## 💻 Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/online-bus-booking-system.git
cd online-bus-booking-system
```

2. Run the application:
```bash
python final_project-1.py
```

> The application will automatically create the SQLite database file (`mydatabase.db`) on the first run.

---

## 🧱 Database Schema

The application uses the following tables:

- `operator` – Stores bus operator information  
- `bus` – Contains bus details (type, capacity, fare)  
- `route` – Stores route and station details  
- `running` – Tracks bus schedules and seat availability  
- `bookinghistory` – Stores passenger booking records  

---

## 🧑‍💼 Usage Instructions

### For Passengers:
- Select **"Seat Booking"** from the main menu  
- Enter **From**, **To**, and **Date**  
- Choose a bus from the list  
- Enter passenger details  
- Confirm and print your ticket  

### For Admin:
- Select **"Update Database"** from the main menu  
- Login with credentials:  
  - **Username**: `j`  
  - **Password**: `123`  
- Access admin functions:  
  - Add/Edit Operators  
  - Manage Buses  
  - Configure Routes  
  - Set Running Schedules  

---

## 🖼️ Screenshots

*(Include screenshots of the main interface, booking flow, and admin panel here if available)*

---

## 📁 Project Structure

```bash
online-bus-booking-system/
├── final_project-1.py       # Main application file
├── mydatabase.db            # SQLite database (created on first run)
├── Bus.png                  # Application logo
├── home.png                 # Home button icon
└── README.md                # Project documentation
```

---

## ⚙️ Customization

You can customize the app by editing:

- **Admin credentials**: in the `loginn` method  
- **Bus types and fares**: in the `bus` method  
- **Date format and validation** logic  

---

## ⚠️ Known Issues

- Date validation can be improved  
- Error messages could be more user-friendly  
- Only one admin account supported currently  

---

## 🌱 Future Enhancements

- Payment gateway integration  
- User account system and authentication  
- Admin-side reporting features  
- Multi-language support  

---

## 🙏 Acknowledgments

- Special thanks to **Dr. Mahesh Kumar** for his guidance  
- Tkinter documentation  
- Python community and tutorials  
