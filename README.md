# 🚤 Boat Reservation & Management System

A comprehensive web-based **Boat Reservation & Management System** built with **PHP** and **MySQL**. The system streamlines boat ticket reservations, passenger management, employee operations, and administrative reporting through an intuitive online platform.

---

# 📖 Overview

The Boat Reservation & Management System is designed to digitize and simplify the management of passenger boat services.

Passengers can register, browse available boats and routes, reserve tickets online, and monitor their bookings, while administrators and employees can efficiently manage boats, passengers, reservations, and financial records.

The system provides a centralized platform that improves operational efficiency, minimizes manual processes, and enhances the overall booking experience.

![8](https://github.com/riley071/Boat-Managment-system-PHP/assets/81653537/29304e6a-5a3f-45e2-a7a4-82c718d6a4ea)
---

# ✨ Key Features

## 👤 Passenger Portal

- User registration and secure login
- Browse available boats and routes
- Online ticket reservation
- Ticket cancellation
- View and print booked tickets
- Update personal profile
- View booking history

---

## 🛥️ Boat Management

Administrators and employees can:

- Add new boats
- Update boat information
- Delete boats
- Manage routes
- Set fares
- Configure departure times
- Define seating capacity
- View and print boat information

Each boat is assigned a unique boat number for easy identification.

---

## 🎫 Ticket Management

The system supports a complete reservation workflow.

### Pending Reservations

- View all pending bookings
- Verify passenger payment codes
- Approve or reject reservations

### Approved Reservations

- View confirmed tickets
- Manage completed bookings

### Ticket Administration

- Update reservations
- Delete reservations
- Monitor booking status

---

## 👥 Passenger Management

Administrators can:

- Register passengers
- Edit passenger information
- Delete passenger records
- Search passenger details
- View complete booking history

---

## 👨‍💼 Employee Management

Administrators can:

- Create employee accounts
- Assign positions
- Manage employee credentials
- Update employee information

Employees have controlled access to:

- Boat management
- Passenger management
- Ticket management
- Reservation approvals

---

## 📊 Accounting Dashboard

The system includes an accounting module that provides:

- Total ticket sales
- Reservation statistics
- Paid vs Pending reservations
- Revenue overview
- Interactive charts
- Export chart images

Sales are recorded only after reservation approval.

---

## 📈 Dashboard

The dashboard provides an overview of system activity, including:

- Total passengers
- Total boats
- Active reservations
- Pending reservations
- Approved tickets
- Revenue summary

---

# 🛠 Technology Stack

### Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

### Backend

- PHP

### Database

- MySQL

### Server

- Apache (XAMPP)

---

# 📂 Project Structure

```
Boat-Management-System/
│
├── admin/
├── employee/
├── passenger/
├── database/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── includes/
├── index.php
└── README.md
```

---

# 🚀 Available Features

- ✅ Admin Dashboard
- ✅ Employee Dashboard
- ✅ Passenger Portal
- ✅ Boat Management
- ✅ Route Management
- ✅ Passenger Management
- ✅ Employee Management
- ✅ Online Ticket Booking
- ✅ Ticket Approval System
- ✅ Pending & Approved Reservations
- ✅ Ticket Printing
- ✅ Reservation Cancellation
- ✅ Profile Management
- ✅ Search Boats
- ✅ Accounting Module
- ✅ Revenue Dashboard
- ✅ Responsive Interface

---

# ⚙️ System Requirements

| Requirement | Version |
|-------------|---------|
| PHP | 5.6, 7.4, 8.x |
| Database | MySQL |
| Server | XAMPP / WAMP / LAMP |
| Browser | Chrome, Firefox, Edge |

---

# 📥 Installation

## 1. Clone the repository

```bash
git clone https://github.com/riley071/Boat-Managment-system-PHP.git
```

Or download the ZIP file and extract it.

---

## 2. Move the project

Copy the project folder into your web server directory.

For XAMPP:

```
xampp/htdocs/
```

---

## 3. Create the database

Open:

```
http://localhost/phpmyadmin
```

Create a new database using the name provided in:

```
01 LOGIN DETAILS & PROJECT INFO.txt
```

---

## 4. Import the database

Import the SQL file located in:

```
DATABASE FILE/
```

---

## 5. Configure the database

Update your database connection settings if necessary.

Example:

```php
$db = new mysqli("localhost", "root", "", "database_name");
```

---

## 6. Start the application

Visit:

```
http://localhost/Boat-Managment-system-PHP/
```

Use the login credentials provided inside:

```
01 LOGIN DETAILS & PROJECT INFO.txt
```

---

# 📸 Screenshots

> Add screenshots of the dashboard, reservation page, passenger portal, and accounting dashboard here.

---

# 🔒 User Roles

### Administrator

- Full system access
- Manage boats
- Manage passengers
- Manage employees
- Approve reservations
- View accounting reports
- Manage tickets

### Employee

- Manage boats
- Manage passengers
- View reservations
- Approve tickets
- Update bookings

### Passenger

- Register account
- Book tickets
- Cancel bookings
- View tickets
- Print tickets
- Update profile

---

# 💡 Future Improvements

- Online payment gateway integration
- QR Code ticket verification
- Email ticket confirmations
- SMS notifications
- Mobile-responsive redesign
- Multi-branch support
- Seat selection interface
- Live boat tracking
- REST API
- Analytics dashboard

---

# 👨‍💻 Author

**Emmanuel Matewere**

*Full-Stack Developer • ICT Professional • Systems Builder*

- **GitHub:** https://github.com/riley071
- **Email:** emzomatewere@gmail.com

---

# 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project in accordance with the license.



