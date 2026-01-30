# DVMD Emergency Management System

A web-based emergency response platform designed to help Malaysian local authorities coordinate disaster and incident management across multiple administrative levels.

## 📋 Project Overview

The DVMD Emergency Management System is a comprehensive web application built for Malaysian administrative structure, enabling efficient emergency reporting, tracking, and response coordination between different government levels including Pejabat Daerah, Penghulu, and Ketua Kampung.

## 🏗️ System Architecture

### Core Components

- **PHP Backend** (83.2%): Server-side logic and business rules
- **CSS Frontend** (14.5%): Styling and responsive design
- **JavaScript** (2.1%): Client-side interactivity
- **Database Integration**: MySQL-based data management

### Directory Structure
├── css/ # Stylesheets
├── database/ # Database schemas and scripts
├── dvmd/ # Core application modules
├── images/ # System images and assets
├── includes/ # Shared PHP includes and libraries
├── js/ # JavaScript functionality
├── management/ # Administrative modules
├── vendor/ # Third-party dependencies
└── [PHP files] # Individual application pages


## 👥 User Roles & Dashboards

The system implements role-based access control with specialized dashboards:

1. **Pejabat Daerah Dashboard** (`pejabatdaerahdashboard.php`) - District-level administration
2. **Penghulu Dashboard** (`penghuludashboard.php`) - Sub-district level management
3. **Ketua Kampung Dashboard** (`ketuakampungdashboard.php`) - Village-level administration

## 🔑 Authentication System

- **Login/Logout**: Secure session management (`loginpage.php`, `logout.php`)
- **Registration**: New user onboarding (`registerpage.php`)
- **Password Recovery**: Forgot password flow with OTP verification (`forgotpasswordpage.php`, `verifyOTPpage.php`, `resetpasswordpage.php`)

## 🚨 Emergency Management Features

- **Incident Reporting**: Multi-level reporting system
- **Data Export**: Export incident data (`export_incidents.php`)
- **Report Generation**: Dynamic report creation (`get_reports.php`)
- **Weather Integration**: Real-time weather data API (`weather_api.php`)

## 🛠️ Technical Stack

- **Primary Language**: PHP
- **Frontend**: CSS, JavaScript
- **Database**: MySQL (implied from structure)
- **Version Control**: Git

## 🚀 Getting Started

### Prerequisites

- Web server (Apache, Nginx, or equivalent)
- PHP 7.0+ with MySQL support
- MySQL database server

### Installation

1. Clone the repository to your web server directory
2. Import database schema from `database/` folder
3. Configure database connection settings
4. Set appropriate file permissions
5. Access the application via web browser

## 📊 Data Management

The system includes comprehensive data handling capabilities with proper separation between presentation, business logic, and data access layers as evidenced by the structured directory organization.

## 🔐 Security Considerations

- Secure authentication flow with password reset functionality
- Role-based access control to sensitive data
- Session management for user state

## 🌐 Integration Points

- **Weather API**: External weather data integration for emergency planning
- **Reporting System**: Flexible data export and report generation

## 📈 Development Status

Initial commit established on January 30, 2026 with foundational structure for a multi-level emergency management system tailored to Malaysian administrative requirements.

---

*This system appears designed to facilitate coordinated emergency response across different levels of Malaysian local government, with specific attention to hierarchical reporting structures common in Malaysian administration.*
