# 🩺 AppoinDent

<div align="center">

[![Flutter Version](https://img.shields.io/badge/Flutter-%3E%3D3.41.1-02569B?style=for-the-badge&logo=flutter)](https://flutter.dev)
[![Dart Version](https://img.shields.io/badge/Dart-%3E%3D3.3.0-0175C2?style=for-the-badge&logo=dart)](https://dart.dev)
[![Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture%20%2B%20BLoC-ff69b4?style=for-the-badge)](https://bloclibrary.dev)
[![Backend](https://img.shields.io/badge/Backend-Firebase-FFCA28?style=for-the-badge&logo=firebase)](https://firebase.google.com)
[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-02569B?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-Proprietary-blueviolet?style=for-the-badge)](#-license)

### Enterprise Dental Practice Management Platform

**A modern multi-tenant platform designed to streamline dental clinic operations, appointment scheduling, patient management, billing, and administrative operations.**

</div>

---

## 📖 Overview

**AppoinDent** is a professional dental practice management platform built to support modern dental clinics and their day-to-day operations.

The platform combines a **cross-platform mobile application for dentists and clinical staff** with a dedicated **Web Administration Dashboard** for centralized clinic and platform management.

AppoinDent is designed around a **multi-tenant architecture**, allowing multiple clinics to operate independently while maintaining strict separation of their data and operational environments.

The platform is built using **Flutter, Clean Architecture, BLoC, and Firebase**, providing a scalable foundation for reliable clinical and administrative workflows.

---

## 🚀 Key Features

### 🔐 Authentication & Security

- **Multi-Tenant Authentication** — Secure authentication designed for clinic-based access.
- **Email & Password Authentication** — Standard secure account authentication.
- **OTP Authentication** — One-time password authentication support.
- **Google Sign-In** — Convenient authentication using Google accounts.
- **Biometric Authentication** — Face ID / Touch ID support for protected areas.
- **Firebase App Check** — Application integrity and API access protection.
- **Secure Local Storage** — Sensitive authentication data is securely stored on the device.
- **Session Management** — Secure handling of authenticated user sessions.
- **English & Arabic Support** — Full localization with RTL support.

---

### 📅 Advanced Appointment Management

AppoinDent provides a flexible appointment scheduling system designed for real-world dental clinic workflows.

- **Single Appointment Booking** — Standard appointment scheduling.
- **Range-Based Booking** — Support for appointments spanning multiple time periods.
- **Flexible Appointment Durations** — Suitable for procedures requiring more than a standard time slot.
- **Conflict Prevention** — Automatically detects overlapping appointments before confirmation.
- **Interactive Calendar** — Visual scheduling interface with appointment and slot status.
- **Appointment History** — Access to previous and completed appointments.
- **Appointment Reminders** — Automated local and scheduled reminders.
- **Real-Time Scheduling Validation** — Appointment availability is verified before reservations are confirmed.

---

### 👥 Patient Management

- **Patient Profiles** — Centralized patient information and demographic records.
- **Medical History** — Maintain relevant patient medical information.
- **Treatment History** — Track patient treatments and clinical records.
- **Patient Appointment History** — View previous and scheduled appointments.
- **Clinic-Isolated Patient Data** — Patient information remains isolated within its respective clinic.
- **Efficient Patient Search & Management** — Designed for quick access to patient information during daily operations.

---

### 🏥 Multi-Clinic Management

AppoinDent is designed to support multiple clinics through a tenant-based management model.

- **Multi-Tenant Architecture** — Multiple clinics can operate independently on the same platform.
- **Clinic Data Isolation** — Strict separation between clinic data.
- **Clinic Management** — Centralized management of registered clinics.
- **Clinic Settings & Information** — Manage clinic-specific configuration and details.
- **Subscription-Based Clinics** — Support for clinic subscription plans.
- **Tier-Based Plans** — Different subscription tiers can be configured for participating clinics.

---

### 💳 Billing & Financial Management

- **Billing Management** — Manage clinic billing workflows.
- **Financial Records** — Track relevant financial information.
- **Revenue Reporting** — Generate clinic revenue reports.
- **Financial Analytics** — Visualize financial data through interactive dashboards.
- **Excel Reports** — Export financial and operational data to Excel-compatible spreadsheets.
- **Schedule & Report Export** — Export relevant clinic data for external use.

---

### 📊 Analytics & Dashboards

AppoinDent provides interactive dashboards to help clinic staff and administrators understand operational data.

- **Clinic Performance Metrics**
- **Appointment Statistics**
- **Financial Analytics**
- **Interactive Charts**
- **Operational Data Visualization**
- **Administrative Platform Metrics**

---

## 🖥️ Web Administration Dashboard

AppoinDent includes a dedicated **Web Admin Dashboard** for centralized platform administration.

The administration portal provides tools for managing the broader AppoinDent ecosystem rather than individual daily clinical workflows.

### Administration Capabilities

- **Admin Authentication**
- **Clinic Registration & Management**
- **Multi-Clinic Administration**
- **Subscription Management**
- **Subscription Tier Configuration**
- **Platform Analytics**
- **System Activity & Audit Logs**
- **Administrative Controls**
- **Centralized Platform Monitoring**

### 🌐 Live Admin Portal

The production administration portal is hosted on Firebase:

**[Open AppoinDent Admin Portal](https://dental-94235.web.app)**

> Administrative access is restricted to authorized users.

---

## 🏗️ Architecture

AppoinDent follows a **Clean Architecture + BLoC** approach to maintain separation of responsibilities and support long-term scalability.

### High-Level Architecture

```text
┌─────────────────────────────────────────┐
│             Presentation                │
│        Flutter UI / BLoC / Cubit        │
└───────────────────┬─────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────┐
│                Domain                   │
│      Business Logic / Use Cases         │
└───────────────────┬─────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────┐
│                 Data                    │
│    Repositories / Remote / Local Data   │
└───────────────────┬─────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────┐
│          Firebase & Cloud Services      │
└─────────────────────────────────────────┘
```

### Architectural Principles

- **Clean Separation of Concerns**
- **BLoC-Based State Management**
- **Dependency Inversion**
- **Repository-Based Data Access**
- **Centralized Dependency Management**
- **Immutable State Management**
- **Business Logic Separation**
- **Multi-Environment Support**
- **Testable Application Structure**

---

## 🛠️ Technology Stack

| Category | Technologies |
| :--- | :--- |
| **Framework** | Flutter |
| **Language** | Dart |
| **Architecture** | Clean Architecture |
| **State Management** | BLoC / Cubit |
| **Backend** | Firebase |
| **Authentication** | Firebase Authentication |
| **Database** | Cloud Firestore / Firebase Database |
| **Storage** | Firebase Storage |
| **Security** | Firebase App Check, Secure Storage, Biometric Authentication |
| **Networking** | Dio |
| **Navigation** | GoRouter |
| **Localization** | Easy Localization / Internationalization |
| **Charts** | FL Chart |
| **Calendar** | Calendar Date Picker |
| **Reporting** | Excel Export & Office Charting |
| **Platforms** | Android, iOS, Web |

---

## 🌍 Localization

AppoinDent supports multiple languages to accommodate different clinical environments.

### Supported Languages

- 🇬🇧 **English**
- 🇸🇦 **Arabic**

The application includes:

- Full UI localization
- RTL support for Arabic
- Localized dates and formatting
- Language-aware user experience

---

## 🔒 Security & Data Protection

Security is a core part of the platform, particularly because AppoinDent handles clinic and patient-related information.

The platform incorporates multiple layers of protection:

- **Firebase App Check** for application integrity and access protection.
- **Secure Local Storage** for sensitive local credentials and tokens.
- **Biometric Authentication** for additional device-level protection.
- **Multi-Tenant Data Isolation** to separate clinic information.
- **Firestore Security Policies** to enforce tenant-level access.
- **Authenticated Access Control** for protected application areas.
- **Environment Separation** between development and production configurations.

> AppoinDent is proprietary commercial software. Access to the production system and administrative functionality is restricted to authorized users.

---

## 📱 Supported Platforms

AppoinDent is designed as a multi-platform Flutter application.

| Platform | Availability |
| :--- | :--- |
| 🤖 Android | ✅ Supported |
| 🍎 iOS | ✅ Supported |
| 🌐 Web | ✅ Admin Portal |
| 🖥️ Desktop | Not currently targeted |

---

## 🧪 Quality & Reliability

The project follows standard software engineering practices to maintain code quality and application reliability.

### Quality Practices

- Unit testing
- BLoC testing
- Static code analysis
- Automated code formatting
- Generated model serialization
- Structured application architecture
- Environment-specific configurations
- Centralized dependency management

---

## 📈 Platform Capabilities

At its current stage, AppoinDent provides an integrated ecosystem covering:

```text
                    AppoinDent
                          │
          ┌───────────────┴───────────────┐
          │                               │
     Mobile Platform                 Admin Platform
          │                               │
    ┌─────┼─────┐                 ┌───────┼────────┐
    │     │     │                 │       │        │
Appointments Patients        Clinics  Plans   Analytics
    │     │     │                 │       │        │
    └─────┴─────┘                 └───────┴────────┘
          │                               │
          └───────────────┬───────────────┘
                          │
                     Firebase Cloud
```

The system brings together:

- 📅 Appointment Scheduling
- 👥 Patient Management
- 🏥 Multi-Clinic Operations
- 💳 Billing & Financial Management
- 📊 Analytics & Reporting
- 🔐 Authentication & Security
- 🖥️ Web Administration
- 🌍 Multi-Language Support
- 🔔 Appointment Notifications

---

## 🔮 Product Direction

AppoinDent is continuously evolving as a professional dental practice management platform.

The architecture is designed to support the future expansion of:

- Advanced clinic management capabilities
- Additional analytics and reporting
- Expanded financial workflows
- Enhanced scheduling functionality
- Additional administrative tools
- Further platform automation

---

## 📸 Screenshots & Product Preview

Screenshots and product previews can be added here to showcase the platform without exposing proprietary source code.

### Mobile Application

*Coming soon.*

### Web Administration Dashboard

*Coming soon.*

---

## 🔐 License

**Proprietary Software — All Rights Reserved**

AppoinDent is proprietary commercial software.

The source code, application architecture, business logic, database configuration, backend implementation, and other internal components are **not publicly available**.

This public repository exists for **product documentation, technical overview, and project presentation purposes only**.

### Restrictions

You may **not**:

- Copy or redistribute the source code.
- Reverse engineer the application.
- Reproduce the application's business logic or architecture.
- Use the project commercially without authorization.
- Modify or redistribute proprietary components.
- Use project assets or branding without permission.

For licensing or commercial inquiries, please contact the maintainer.

---

## 👤 Maintainer

**Yousef Habbeh**

📧 **Email:** [yousef.habbeh@hotmail.com](mailto:yousef.habbeh@hotmail.com)

📞 **Phone:** <a href="tel:+962781543080">0781543080</a>

🐙 **GitHub:** [yhabbeh](https://github.com/yhabbeh)

---

## 📞 Support & Contact

For commercial inquiries, licensing questions, or product-related requests:

📧 **Email:** [yousef.habbeh@hotmail.com](mailto:yousef.habbeh@hotmail.com)

📞 **Call:** <a href="tel:+962781543080">0781543080</a>

---

<div align="center">

### 🩺 AppoinDent

**Professional Dental Practice Management Platform**

*Built with ❤️ using Flutter, Clean Architecture, BLoC & Firebase.*

</div>
