# Strandly-Your-Friendly-Hair-Fall-Tracker
A full-stack MERN application to help users track hair fall, visualize trends, and receive personalized guidance. 📈

# Strandly: Your Friendly Hairfall Tracker 📈

A full-stack web application built with the MERN stack designed to empower users to proactively manage hair wellness. Strandly allows users to log daily data, visualize their progress on an interactive dashboard, and receive personalized, actionable guidance based on their unique profile and tracking history.

This project was developed as a final-year B.Tech project.

---

## ## Key Features

* **Secure User Authentication:** JWT-based login and registration system to protect user data.
* **Daily Data Logging:** Simple interface for users to log daily hair fall counts and weekly self-assessments.
* **Interactive Dashboard:** A responsive dashboard built with **Chart.js** to visualize hair fall trends and other metrics over time.
* **Smart Guidance Engine:** A rule-based logic engine that analyzes user data to provide personalized lifestyle and product recommendations.
* **Knowledge Base:** A simple CRUD module with articles about hair wellness.

---

## ## Technology Stack

This project is built using the MERN stack and other modern web technologies.

* **Frontend:** React, React Router, Chart.js, Axios
* **Backend:** Node.js, Express.js
* **Database:** MongoDB with Mongoose
* **Authentication:** JSON Web Tokens (JWT)
* **Version Control:** Git & GitHub

---

## ## Getting Started

To get a local copy up and running, follow these simple steps.

### ### Prerequisites

Make sure you have Node.js and npm installed on your machine.
`npm install npm@latest -g`

### ### Installation

1.  **Clone the repo**
    `git clone https://github.com/your_username/strandly.git`
2.  **Navigate to the project directory**
    `cd strandly`
3.  **Install Backend Dependencies**
    `cd server`
    `npm install`
4.  **Install Frontend Dependencies**
    `cd ../client`
    `npm install`
5.  **Setup Environment Variables**
    Create a `.env` file in the `server` directory and add the following:
    ```
    MONGO_URI = 'your_mongodb_connection_string'
    JWT_SECRET = 'your_jwt_secret_key'
    ```
6.  **Run the Application**
    * To run the backend server: `cd server && npm start`
    * To run the React frontend: `cd client && npm start`
