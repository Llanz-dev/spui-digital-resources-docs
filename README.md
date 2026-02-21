# SPUI Digital Resources

SPUI Digital Resources is a web-based digital learning platform developed for
Saint Paul University Iloilo. The system allows students and teachers to access
digital books and academic resources online, replacing traditional printed
materials.

🌐 **Live System:** https://spuidigitalbooks.com

---

## 🎯 Project Overview

SPUI Digital Resources is a production-ready MEAN stack application designed for
Senior High School education. It provides a centralized digital platform where
students and teachers access assigned learning materials, while administrators
maintain full control over system content and user access.

The system is actively used in an academic environment and maintained by the
developer.

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

## 🚀 Live Deployment

The system is live and accessible at:

🔗 https://spuidigitalbooks.com

⚠️ Access to the system is restricted to authorized users only.

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

- ✅ Deployed in production
- ✅ Actively used by students and teachers
- ✅ Maintained and improved by the developer

---

## 👨‍💻 Author

Developed and maintained by  
**Llanz Kenneth Luy**

MEAN Stack Developer | Coding Instructor | Aspiring Computer Vision Engineer

---

## 📄 License

This documentation is provided for portfolio and reference purposes only.
Unauthorized reproduction or commercial use of the system is not permitted.
