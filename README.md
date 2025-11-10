# Smart-hostel-attendance-system
A Flask-based Hostel Management and Attendance Tracking System integrated with Hikvision fingerprint devices and Microsoft SQL Server. It provides real-time attendance logging, student-parent management, and admin dashboards for monitoring hostel activity — including inside/outside status, attendance analytics, and fingerprint enrollment.

📖 Features

✅ Admin Dashboard

Real-time inside/outside student counts

Recent attendance logs

Student & parent management

Fingerprint enrollment and monitoring

✅ Parent Dashboard

View child’s attendance for the past 30 days

Filter logs by date/time/status

Download attendance reports in CSV format

✅ Attendance System

Integration with Hikvision fingerprint devices

REST API endpoint for fingerprint-based check-ins/check-outs

Auto-curfew status tagging (Late In / Early Leave / Normal)

✅ Student Management

Add, edit, or deactivate student records

Assign parent relationships

Manage room/floor/bed allocation

✅ Parent Management

Create and reset parent accounts

Auto-generated secure passwords

Link parents to students

✅ Statistics

Weekly presence graphs

Real-time API for dashboards

✅ Database Setup Helpers

Auto-create required tables (student_fingerprints)

Auto-add missing columns and indexes in students table


🧠 Tech Stack
| Component               | Technology                        |
| ----------------------- | --------------------------------- |
| Backend Framework       | Flask (Python)                    |
| Database                | Microsoft SQL Server              |
| ORM/DB Driver           | pyODBC                            |
| Authentication          | Flask Session + Werkzeug Security |
| Fingerprint Integration | Hikvision API Client              |
| Frontend                | HTML, CSS, Jinja2 Templates       |
| Data Format             | JSON, CSV                         |
| Hosting                 | Localhost or VPS with MSSQL       |
