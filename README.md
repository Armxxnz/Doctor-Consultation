<div align="center">

# 🩺 Doctor Consultation System

### A Java-based Doctor Consultation & Appointment Management System

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Java%20Swing-GUI-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/JDBC-Connectivity-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/NetBeans-IDE-1B6AC6?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white">
</p>

<p>
  <b>Doctor Consultation System</b> is a desktop-based healthcare application
  developed using Java Swing and MySQL that connects patients with doctors
  and simplifies appointment management.
</p>

<br>

<a href="#-features">Features</a> •
<a href="#-technologies-used">Technologies</a> •
<a href="#-system-workflow">Workflow</a> •
<a href="#-installation">Installation</a> •
<a href="#-screenshots">Screenshots</a> •
<a href="#-future-enhancements">Future Enhancements</a>

</div>

---

## 📌 About The Project

The **Doctor Consultation System** is a desktop application designed to
digitize the traditional doctor consultation and appointment process.

The system provides separate interfaces for **patients and doctors**.

Patients can register, log in, browse doctors according to their specialization,
book appointments and view their bookings.

Doctors can register, create their professional profile, upload a profile
picture, log in and view their patient appointments.

The application uses **MySQL** for persistent data storage and **JDBC** for
communication between the Java application and the database.

---

# ✨ Features

## 👤 Patient Features

<table>
<tr>
<td width="50%">

### 🔐 Authentication

- User Registration
- User Login
- Forgot Password
- OTP Verification
- Password Reset
- Change Password
- Logout

</td>

<td width="50%">

### 📅 Appointment Management

- Browse Doctors
- Search by Specialization
- View Doctor Information
- Book Appointments
- Select Appointment Date
- Select Appointment Time
- View Bookings

</td>
</tr>
</table>

---

## 👨‍⚕️ Doctor Features

<table>
<tr>
<td width="50%">

### 📝 Doctor Registration

- Doctor Registration
- Professional Information
- Email Registration
- Password Creation
- Specialization Selection
- Profile Picture Upload

</td>

<td width="50%">

### 📋 Doctor Dashboard

- Doctor Login
- View Profile
- View Patient Bookings
- View Appointment Information
- Change Password
- Logout

</td>
</tr>
</table>

---

## 🏥 Available Specializations

The system supports multiple medical specializations:

<div align="center">

| 🩺 Specialization |
|---|
| Cardiology |
| Dermatology |
| Neurology |
| Orthopedics |
| Pediatrics |
| General Medicine |

</div>

---

# 🛠️ Technologies Used

<div align="center">

| Technology | Purpose |
|---|---|
| ☕ **Java** | Application Development |
| 🖥️ **Java Swing** | Graphical User Interface |
| 🎨 **NetBeans GUI Builder** | UI Design |
| 🗄️ **MySQL** | Database |
| 🔌 **JDBC** | Database Connectivity |
| 📧 **JavaMail** | OTP / Email Functionality |
| 🖼️ **ImageIcon** | Profile Picture Handling |
| 🔧 **Git & GitHub** | Version Control |

</div>

---

# 🏗️ System Architecture

```text
                         ┌───────────────────────────┐
                         │   Doctor Consultation     │
                         │          System           │
                         └─────────────┬─────────────┘
                                       │
                    ┌──────────────────┴──────────────────┐
                    │                                     │
             ┌──────▼──────┐                       ┌──────▼──────┐
             │    PATIENT   │                       │    DOCTOR   │
             │    MODULE    │                       │    MODULE   │
             └──────┬───────┘                       └──────┬───────┘
                    │                                      │
          ┌─────────┼─────────┐                  ┌─────────┼─────────┐
          │         │         │                  │         │         │
       Register   Login    Booking            Register   Login    Profile
          │         │         │                  │         │         │
          └─────────┼─────────┘                  └─────────┼─────────┘
                    │                                      │
                    └────────────────┬─────────────────────┘
                                     │
                              ┌──────▼──────┐
                              │    JDBC     │
                              │  DBLoader   │
                              └──────┬──────┘
                                     │
                              ┌──────▼──────┐
                              │    MySQL    │
                              │  Database   │
                              └─────────────┘
