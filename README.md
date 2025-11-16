# BackStagePassWebsite2

Backstage Pass – README
Project Overview
Backstage Pass is a web-based admin panel designed for managing artist profiles, bookings, and user sign-up requests for an entertainment and event management platform. The system enables admins to approve bookings, manage event information, upload artist images, and control access for users.
The platform ensures smooth communication between event organizers and artists by providing tools for monitoring artist details, booking statuses, and verification logs.

Features
1. Admin Authentication
•	Secure login and registration system
•	Password hashing and validation
•	Reset token support for password recovery
2. Artist Management
•	Add, edit, and delete artist profiles
•	Upload and display artist images
•	Manage artist descriptions and contact details
•	View all artists in a structured grid layout
3. Booking Management
•	View booking requests submitted by users
•	Approve or decline event bookings
•	Booking confirmation code support
•	Track booking history and statuses
4. User Sign-Up Management
•	Review new user requests
•	Accept or reject sign-up applications
•	Manage existing users with full CRUD functionality
5. Dashboard
•	Overview of users, bookings, and artists
•	Sidebar and topbar navigation
•	Responsive layout styled similarly to modern admin templates

Tech Stack
Frontend
•	HTML5, CSS3, JavaScript
•	Responsive design with external CSS & JS
Backend
•	PHP (Core PHP)
•	MySQL (phpMyAdmin)
•	mysqli for database interaction

Note: Netlify does not support PHP — must use a PHP-supported hosting service.


Installation Guide
1.Download the XAMPP control panel 
 click on the link to download the control panel https://www.apachefriends.org/download.html
1. Clone or Download the Project
Unzip the folder into your development environment for example XAMPP's htdocs).
2. Import the Database
•	Open phpMyAdmin
•	Create a new database  called backstage_pass database
•	Import the provided .sql file
3. Configure Database
Edit config/db.php:
$host = "localhost";
$user = "root";
$pass = "";
$db   = "backstage_pass database";
4. Start the Server
•	Open XAMPP → Start Apache and MySQL
•	Visit: http://localhost/Website_BSP/

🔐 Security Notes
•	Always use prepared statements (already implemented)
•	Validate uploaded images
•	Keep reset tokens secure
•	Avoid exposing database credentials

📝 Future Improvements
•	Add JWT-based API authentication
•	Introduce artist login dashboards
•	Add event calendar view
•	Implement notifications for bookings
•	Add report generation (PDF, CSV)


License
This project is for educational and personal development purposes. Not intended for commercial use unless modified.

Thank you for using Backstage Pass! 

