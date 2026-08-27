<div align="center">

# 🩺 MEDICARE

### Doctor Consultation & Appointment Management System

<p>
  <i>Connecting Patients with the Right Doctors — Simply, Digitally.</i>
</p>

<br>

<img src="https://img.shields.io/badge/JAVA-SWING-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/JDBC-007396?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NETBEANS-1B6AC6?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white"/>
<img src="https://img.shields.io/badge/STATUS-ACTIVE-2ea44f?style=for-the-badge"/>

<br><br>

<a href="#-about-medicare">About</a> •
<a href="#-features">Features</a> •
<a href="#-workflow">Workflow</a> •
<a href="#-technology-stack">Technology</a> •
<a href="#-screenshots">Screenshots</a> •
<a href="#-installation">Installation</a> •
<a href="#-roadmap">Roadmap</a>

</div>

---

<div align="center">

> ### Healthcare shouldn't begin with paperwork.
> ### It should begin with a connection.

</div>

---

# 🩺 About MediCare

**MediCare** is a desktop-based **Doctor Consultation and Appointment Management System** developed using **Java Swing, JDBC and MySQL**.

The system digitizes the traditional doctor appointment process by providing separate environments for **patients and doctors**.

Patients can register, log in, discover doctors based on specialization, book appointments and view their bookings.

Doctors can register, create professional profiles, upload profile pictures and view patient appointments.

---

# ✨ Features

<table>
<tr>

<td width="33%" align="center">

## 👤

### PATIENT

- Registration
- Login
- Doctor Discovery
- Specialization Selection
- Appointment Booking
- View Bookings
- Change Password
- Forgot Password
- OTP Verification
- Logout

</td>

<td width="33%" align="center">

## 👨‍⚕️

### DOCTOR

- Doctor Registration
- Doctor Login
- Professional Profile
- Specialization
- Profile Picture
- Patient Bookings
- Appointment Information
- Change Password
- Logout

</td>

<td width="33%" align="center">

## 🗄️

### DATABASE

- MySQL
- JDBC
- User Records
- Doctor Records
- Appointment Records
- Patient Information
- Profile Picture Paths

</td>

</tr>
</table>

---

# 🏥 Medical Specializations

<div align="center">

| ❤️ Cardiology | 🧴 Dermatology | 🧠 Neurology |
|:---:|:---:|:---:|
| Heart & Cardiovascular | Skin & Dermatological | Nervous System |

| 🦴 Orthopedics | 👶 Pediatrics | 🩺 General Medicine |
|:---:|:---:|:---:|
| Bones & Musculoskeletal | Children's Healthcare | General Healthcare |

</div>

---

# 🔄 Workflow

## 👤 Patient Journey

```text
                         ┌───────────────┐
                         │    WELCOME    │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │   REGISTER    │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │     LOGIN     │
                         └───────┬───────┘
                                 │
                         ┌───────▼────────┐
                         │    DASHBOARD   │
                         └───────┬────────┘
                                 │
                         ┌───────▼────────┐
                         │  SPECIALIZATION│
                         └───────┬────────┘
                                 │
                         ┌───────▼────────┐
                         │ DOCTOR LISTING │
                         └───────┬────────┘
                                 │
                         ┌───────▼────────┐
                         │ BOOK APPOINTMENT│
                         └───────┬────────┘
                                 │
                         ┌───────▼────────┐
                         │ VIEW BOOKINGS  │
                         └────────────────┘
