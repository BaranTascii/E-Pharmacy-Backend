# Admin Dashboard - Backend Application

This project implements the backend part of the application, which provides functionality for data management, user authentication, and frontend request processing.

## ## Demo Credentials

To log in and explore the dashboard features, please use the following pre-configured admin vendor account:

* **Email Address:** `vendor@gmail.com`
* **Password:** `1234567`

---

## ## Main components and functionality

* **API Endpoints:** A set of API endpoints has been implemented for interaction with the frontend. It includes endpoints for:
    * User login.
    * Retrieving data (e.g., list of boards, columns, cards).
    * Saving and updating data (creating new boards, adding columns, editing cards, etc.).
    * Deleting data.
* **Authentication and Authorization:** Mechanisms have been implemented for secure user authentication and authorization of their actions based on their access rights.
* **Data Storage:** A database structure and corresponding models have been developed for efficient storage of information about boards, columns, and cards. CRUD (Create, Read, Update, Delete) operations are provided for this data.
* **Data Validation and Processing:** Input data from the frontend is validated to ensure its correctness and integrity before being saved. Error handling and appropriate messages are provided in response to incorrect input or other problems.
* **Frontend Request Processing:** The backend processes various requests coming from the frontend, executing the appropriate business logic.
* **Database Integration:** A connection to the database is configured and logic is implemented to execute queries to it to retrieve, store, and update data.

## ## Technologies Used

* **Node.js** – JavaScript runtime environment
* **Express.js** – Minimalist and flexible web application framework
* **MongoDB** – NoSQL database for structured data persistence
* **Swagger UI** – API specification and interactive live testing documentation

## ## Installation and Startup

Follow these simple steps to spin up the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/BaranTascii/E-Pharmacy-Backend

# 2. Navigate to the project folder and install dependencies
npm install

# 3. Start the application
npm run start
```

---



