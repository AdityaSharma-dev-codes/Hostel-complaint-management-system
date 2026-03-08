# Hostel Complaint Management System

A comprehensive, web-based platform designed to streamline maintenance and complaint resolution within a hostel environment. Built using Java EE (MVC Architecture), MySQL, and modern Bootstrap 5 for a responsive, user-friendly experience.

## 🌟 Key Features

### 🔐 Role-Based Access Control
- **Students**: Secure registration, complaint submission, real-time status tracking, and a visual history timeline.
- **Maintenance Staff**: Dashboard for assigned tasks, status updates (In-Progress, Resolved), and repair remarks.
- **Admin (Warden)**: Full system oversight, task assignment, analytics reports, and complaint lifecycle management.

### 📋 Complaint Management
- **Status Lifecycle**: SUBMITTED → ASSIGNED → IN_PROGRESS → RESOLVED → CLOSED.
- **Categories**: Electrical, Plumbing, Internet, Cleanliness, Security, and Furniture.
- **Visual Timeline**: Every update is logged with a timestamp and attribution for full transparency.

### 📊 Analytics Dashboard
- **Key KPIs**: Total complaints, pending vs. closed counts, and average resolution time.
- **Data Visualization**: Status distribution and category-wise analysis for better resource allocation.

## 🏗️ Technical Architecture (MVC)

- **Model**: Java POJOs in `com.hostel.model` and Data Access Objects in `com.hostel.dao` for robust data handling.
- **View**: Modern, responsive JSP files using **Bootstrap 5**, **FontAwesome 6**, and standard JSTL tags.
- **Controller**: Java Servlets in `com.hostel.controller` managing application logic and request routing.
- **Security**: Centralized `AuthFilter` for role-based URL protection and session validation.

## 🛠️ Technology Stack

- **Backend**: Java 11+, Servlets 4.0, JSP 2.3
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5, FontAwesome 6
- **Database**: MySQL 8.0+
- **Build Tool**: Apache Maven
- **Server**: Apache Tomcat 7/8/9+

---
**Status**: Fully Implemented & Ready for Deployment ✅
