# 🏆 Sportify-Project
Sportify : The platform for sports consultation for the Omnes community. This project is designed as an innovative website for the Omnes Education community to book online appointments with sports specialists.

---

## 📜 About The Project
The goal of Sportify is to create a seamless online platform where clients can easily connect with sports professionals. Clients can browse a comprehensive list of all available specialists, select their preferred one, and view detailed information such as their CV, contact details, and weekly schedule to check for availability. After scheduling an appointment, the client receives a confirmation. The platform is open to all members of the Omnes Education community and also supports live communication with specialists who are online.

---

## ✨ Features
* **Browse Specialists**: Users can view a complete list of all sports personnel available on the Sportify platform.
* **Detailed Specialist Profiles**: Each specialist has a profile page showing their CV, contact information, and a weekly calendar displaying their availability for appointments.
* **Online Booking**: Clients can select a specialist and book an available time slot for a sports consultation directly through the platform.
* **Appointment Confirmation**: After a booking is made, the client receives a confirmation of their appointment.
* **Live Communication**: If a specialist is marked as available online, clients have multiple ways to communicate with them directly:
    * **Text Chat**: A real-time chat room for messaging.
    * **Videoconference**: Live video and audio calls.
    * **Email**: A traditional email communication option.

---

## 🛠️ Tech Stack
The project is built with a classic web stack, as inferred from the repository structure.

* **Frontend**: HTML, CSS, JavaScript 
* **Backend**: PHP
* **Database**: SQL (likely MySQL/MariaDB, based on the `sportify.sql` file)

---

## 📁 Project Structure
The repository is organized with distinct folders for different parts of the application:
* **`/php/`**: Contains all the backend server-side logic, including user authentication, database configuration, and appointment processing.
* **`/javascript/`**: Holds the client-side scripts for interactive features like the chat, user login, and search functionality.
* **`/styles/`**: Contains the CSS files for styling the web pages.
* **`/images/` & `/cv/`**: Store static assets like images and specialist CVs.
* **`sportify.sql`**: The SQL database dump file required to set up the database schema and initial data.

---

## 🚀 Getting Started
To get a local copy up and running, follow these steps.

### Prerequisites
* A local web server environment like XAMPP, WAMP, or MAMP (which includes Apache, MySQL, and PHP).
* A web browser.

### Installation & Execution
1.  **Download the Project**: Clone the repository or download the source code files into a folder.
2.  **Setup the Database**:
    * Start the Apache and MySQL services from your XAMPP/WAMP control panel.
    * Open `phpMyAdmin` (usually at `http://localhost/phpmyadmin`).
    * Create a new database.
    * Select the new database and go to the "Import" tab.
    * Upload and import the `sportify.sql` file to create all the necessary tables and data.
3.  **Configure the Connection**:
    * Open the `/php/config.php` or a similar database connection file in the project.
    * Update the database credentials (host, username, password, database name) to match your local setup.
4.  **Run the Project**:
    * Place the entire project folder inside your web server's root directory (e.g., `C:/xampp/htdocs` for XAMPP).
    * Open your web browser and navigate to `http://localhost/your-project-folder-name/`. The `index.html` page should load.
