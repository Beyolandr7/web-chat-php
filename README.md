# 💬 PHP Group Chat Application

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

A web-based chat and group messaging application built with core PHP. This project features user authentication, dynamic group chats, and an administrative dashboard to manage users and conversations. 

*Originally developed as a Midterm Project (UTS).*

## ✨ Features

* **🔐 User Authentication:** Secure login, registration, and password management (`change_password.php`).
* **👥 Group Chats:** Users can view group details and participate in group messaging (`detail_grup.php`, `chat.php`).
* **⚙️ Admin Panel:** Dedicated administrator dashboard for managing the platform (`/admin`).
* **🧩 Modular Structure:** Object-Oriented/Modular design using dedicated classes and configuration files (`/class`, `/config`).

## 📂 Project Structure

```text
├── admin/                 # Administrator dashboard and management scripts
├── class/                 # PHP Classes for object-oriented logic
├── config/                # Database connection and environment configurations
├── images/                # Static image assets
├── js/                    # Client-side JavaScript for dynamic interactions
├── process/               # Backend action handlers (form submissions, API endpoints)
├── change_password.php    # User password update interface
├── chat.php               # Main chat interface
├── detail_grup.php        # Group information and member list
├── index.php              # Landing page / Home
└── login.php              # User authentication gateway
