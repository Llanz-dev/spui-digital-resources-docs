# SPUI Digital Resources

SPUI Digital Resources is a web-based digital learning platform developed for
Saint Paul University Iloilo. The system allows students and teachers to access
digital books and academic resources online, replacing traditional printed
materials.

---

## 🎯 Project Overview

SPUI Digital Resources is a production-ready MEAN stack application designed for Senior High School education. It has been successfully deployed as a pilot system and utilized in a real academic environment for one month, demonstrating its reliability and effectiveness. The platform provides a centralized digital space where students and teachers can seamlessly access assigned learning materials, while administrators maintain full control over content management and user access.

---

## 🧱 Tech Stack

**Frontend**
- Angular
- Deployed via AWS S3 + CloudFront

**Backend**
- Node.js
- Express.js (JavaScript, ES Modules)
- Hosted on AWS Elastic Beanstalk

**Database**
- MongoDB Atlas

**Infrastructure**
- AWS S3 (static hosting)
- AWS CloudFront (CDN)
- AWS Elastic Beanstalk (Backend API)
- HTTPS via AWS ACM

---

## 👤 User Roles

### Admin
- Manually created admin accounts (no public registration)
- Full system access and control
- Manage all digital books and resources
- Review, edit, and manage content uploaded by teachers
- Manage book metadata, cover images, and availability
- Control user access and permissions

### Teacher
- Secure login access
- Upload and manage their own digital books and resources
- Manage book metadata and cover images for their uploads
- Use the platform to support classroom instruction

### Student
- Secure login access
- Read assigned digital books and academic resources
- Access materials anytime through the web platform

---

## ✨ Key Features

- Role-based authentication and authorization
- Teacher-managed content with admin oversight
- Digital book and resource management
- Book cover image upload support
- Clean, modern reading interface
- Cloud-based deployment with scalable architecture
- Clear separation of frontend and backend services

---

## 🚀 Deployment

🔒 The system was deployed in a controlled production environment (private access)

- ✅ Completed a successful 1-month pilot implementation
- ✅ Used by real students and teachers in an academic setting
- ✅ Demonstrated reliability and practical usability

---

## 🗂 Project Architecture (High-Level)

- Angular frontend served via AWS S3 and CloudFront
- Frontend communicates with an Express REST API
- Backend deployed using AWS Elastic Beanstalk
- MongoDB Atlas used for persistent data storage

This architecture allows independent scaling, secure data handling, and
efficient content delivery.

---

## 🔐 Source Code Notice

The source code for this project is private due to institutional use,
data privacy, and security considerations.

This repository contains **documentation only**.

---

## 📌 Project Status

- ✅ Completed and successfully deployed
- ✅ Piloted and used in a real academic environment for 1 month
- ✅ Validated through actual usage by students and teachers

---

## 🎥 Demo

Watch the system in action:

👉 [Click here to view the demo](https://drive.google.com/file/d/1sQPQ0Ou6svHHY8nk0UuoPcbXcaa2Ixys/view?usp=drive_link)

> This demo showcases the core features of **SPUI Digital Resources**, including:
> - 📚 Digital book browsing and reading
> - 🧑‍🏫 Admin and Teacher management features

---

## 👨‍💻 Author

Developed and maintained by  
**Llanz Kenneth Luy**

MEAN Stack Developer | Coding Instructor | Aspiring Computer Vision Engineer

---

## 📄 License

This documentation is provided for portfolio and reference purposes only.
Unauthorized reproduction or commercial use of the system is not permitted.
