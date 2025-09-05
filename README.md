# Swasthya Setu: Patient Record Management System

[cite_start]**Swasthya Setu** is a web-based Patient Record Management System developed to streamline the process of storing, retrieving, and managing patient information in a digital format[cite: 14]. [cite_start]This system is designed as a secure and organized solution for handling medical records in clinical settings[cite: 14, 67].

[cite_start]This project was developed by Arya Sachin Mulay (23BIT0131) and Yash Kumar Singh (23BIT0288) in partial fulfillment of the requirements for a Bachelor of Information Technology degree at Vellore Institute of Technology (VIT), Vellore[cite: 14].

## Key Features

* [cite_start]**Secure Login:** Provides a doctor-specific login and patient access[cite: 14].
* [cite_start]**Patient Management:** Allows for a user-friendly interface to add, view, edit, and delete patient records securely[cite: 14, 67].
* [cite_start]**Search Functionality:** Includes a real-time search feature for quick patient lookups[cite: 14].
* [cite_start]**Data Accuracy:** Ensures reliable and structured storage of patient information to minimize manual errors and improve data consistency[cite: 14].

## Technology Stack

[cite_start]The application is a full-stack project built with the following technologies[cite: 14]:

### Backend
* [cite_start]**Runtime:** Node.js [cite: 14]
* [cite_start]**Framework:** Express.js [cite: 14]
* [cite_start]**Database:** MongoDB (using Mongoose for data modeling) [cite: 14]
* **Session Management:** `express-session`

### Frontend
* [cite_start]**Templating Engine:** EJS (Embedded JavaScript Templates) for dynamic rendering of HTML pages[cite: 14].
* [cite_start]**Styling:** HTML5 and CSS3, with Bootstrap for responsive design[cite: 14].
* [cite_start]**Interactivity:** jQuery for DOM manipulation and implementing the real-time search functionality[cite: 14].

## Getting Started

### Prerequisites

* Node.js and npm installed
* MongoDB installed and running locally, or a cloud-hosted instance (e.g., MongoDB Atlas)

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/Swasthya-Setu.git](https://github.com/your-username/Swasthya-Setu.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd Swasthya-Setu
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  If using a local MongoDB, ensure it is running. If using a cloud database, update your `server.js` file with your connection string.
5.  Start the application:
    ```bash
    node server.js
    ```
The application will be available at `http://localhost:3001`.
