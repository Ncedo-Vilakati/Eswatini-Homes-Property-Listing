# 🏡 EswatiniHomes - Property Listing System

A dynamic, web-based real estate platform designed specifically for the Eswatini property market. This system connects buyers, renters, estate agents, and administrators through a centralized, secure, and mobile-responsive portal.

## 📋 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Prerequisites](#-prerequisites)
- [Installation & Setup](#-installation--setup)
- [Database Setup](#-database-setup)
- [Default Login Credentials](#-default-login-credentials)
- [Project Structure](#-project-structure)
- [Documentation](#-documentation)
- [Security Features](#-security-features)

---

## ✨ Features

### Public Portal (Guests)
*   **Advanced Search:** Filter properties by location keyword, property type (House, Apartment, Land, etc.), listing type (Sale/Rent), and price range.
*   **Property Details:** View high-quality images, property descriptions, and agent contact information.
*   **Lead Generation:** Submit inquiries directly to agents via a secure contact form.

### Agent Portal
*   **Listing Management:** Create, Read, Update, and Delete (CRUD) their own property listings.
*   **Image Uploads:** Upload up to 3 images per property (JPG/PNG) with server-side MIME validation.
*   **Lead Tracking:** View and manage inquiries from potential buyers/renters.
*   **Commission Tracking:** Record closed deals and automatically calculate 5% commission.

### Admin Portal
*   **Moderation:** Approve or reject property listings (with mandatory rejection reasons).
*   **User Management:** Manage agent accounts (Approve/Suspend).
*   **Dashboard Statistics:** View real-time metrics on total properties, pending listings, registered agents, and total leads.
*   **Soft Deletion:** Deleting an agent safely deletes their listings while preserving historical deal and lead data.

---

## 🛠 Tech Stack
*   **Frontend:** HTML5, CSS3, JavaScript, Boxicons
*   **Backend:** PHP 8.x
*   **Database:** MariaDB / MySQL (via XAMPP)
*   **Server:** Apache

---

## ⚙️ Prerequisites
Before you begin, ensure you have the following installed:
*   [XAMPP](https://www.apachefriends.org/index.html) (or WAMP/MAMP) with PHP 8.x and MariaDB/MySQL.
*   [Git](https://git-scm.com/) (optional, for cloning).
*   A modern web browser (Chrome, Firefox, Edge).

---

## 🚀 Installation & Setup

1. **Clone the repository** (or download the ZIP):
   ```bash
   git clone https://github.com/YourUsername/Eswatini-Homes-Property-Listing.git
