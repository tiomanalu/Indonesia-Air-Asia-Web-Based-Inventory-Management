✈️ Cabin Crew Inventory Management System
🌟 Overview
The Cabin Crew Inventory Management System is a 🌐 web-based application developed to automate and streamline inventory management processes for cabin crew operations. This project addresses inefficiencies and inaccuracies inherent in manual inventory systems, providing an integrated platform for administrators, cabin crew, and management to manage inventory seamlessly.

✨ Features
🔑 For Administrators:
✅ Authentication and role-based access.
🛠️ Manage inventory (add, edit, delete items).
📩 Confirm or reject cabin crew requests.
📊 Export inventory and request data in PDF/Excel formats.
👥 View and update cabin crew profiles.
🎯 For Cabin Crew:
🔒 Authenticate via AirAsia Google accounts.
📦 Submit requests and purchase items.
👍 Confirm receipt of items.
🔍 View the status of requests and purchases.
✏️ Update personal data and size information.
🏢 For Management:
📈 Monitor inventory status and levels.
✅ Approve or reject cabin crew requests.
📂 View and export data on inventory and requests.
🗂️ Access cabin crew profiles, including history of requests and purchases.
🛠️ Technology Stack
Frontend & Backend Framework: Laravel (PHP) v10.48.7
Database: MySQL
Server: Apache/2.4.47 (Win64)
Dependencies:
📄 barryvdh/laravel-dompdf
🌐 guzzlehttp/guzzle
📊 maatwebsite/excel
🔐 spatie/laravel-permission
🛠️ Others as listed in the integrated module specifications.
🖥️ System Requirements
💻 Operating System: Windows 11
⚙️ Laravel Framework: Version 10.48.7
🐘 PHP: Version 8.1.5
🗄️ Database: MySQL
📦 Dependency Management: Composer
🚀 Installation
Clone the repository to your local environment. 🖥️
Install required dependencies using Composer:
bash
Copy
Edit
composer install
Configure the .env file with your database credentials and necessary configurations. 📝
Run migrations to set up the database:
bash
Copy
Edit
php artisan migrate
Start the development server:
bash
Copy
Edit
php artisan serve
Access the application at 🌐 http://localhost:8000.
👥 User Roles and Access
🛠️ Administrator: Full control over inventory management and user profiles.
✈️ Cabin Crew: Limited to requesting and purchasing items.
📊 Management: Oversee inventory and approve requests.
📋 Usage
🔒 Authentication
Only users with an AirAsia Google account can log in. 📧
Access is restricted to roles with predefined permissions.
🔄 Key Processes
Request Items: Cabin crew selects items and submits requests for admin approval. 🛒
Inventory Management: Admins manage item availability and updates. 📦
Approval Workflow: Management approves or rejects requests submitted by cabin crew. ✅/❌
📥 Export Options
Data on inventory and requests can be exported in both PDF and Excel formats for reporting and analysis. 📊
🤝 Contribution
Contributions to enhance functionality or address bugs are welcome! 🌟 Please ensure to follow the project's coding standards and submit pull requests with detailed descriptions. 🛠️

👩‍💻 Contributors
We would like to acknowledge the following contributors for their hard work and dedication:

🎉 Tio Manalu
🎉 Yosafat
🎉 Angelica Manurung
📜 License
This project is proprietary to PT. Indonesia AirAsia and is not intended for public distribution. 🔒

For further inquiries or technical support, please contact 📧 support@airasia.com.
