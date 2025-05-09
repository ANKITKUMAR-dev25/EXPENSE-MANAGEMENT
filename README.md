# Expense Management System

## Overview

The Expense Management System is a full-stack web application built using the **MERN** stack (MongoDB, Express, React, Node.js). This app allows users to manage and track their daily expenses, categorize them, and generate reports on their financial spending.

## Features

* **User Authentication**: Secure login and registration using JWT (JSON Web Token) for authentication.
* **Add Expense**: Users can log new expenses, providing details like the amount, category, date, and description.
* **Expense List**: View a list of all recorded expenses with filtering options by date or category.
* **Expense Categories**: Predefined categories such as "Food", "Transportation", "Entertainment", and "Bills".
* **Expense Dashboard**: Visualize your spending through charts and graphs showing the distribution of expenses.
* **Edit/Delete Expenses**: Modify or remove any entries from the expenses list.
* **Responsive Design**: The app is responsive and works well on both desktop and mobile devices.

## Technologies Used

* **Frontend**:

  * React.js
  * React Router for navigation
  * Axios for HTTP requests
  * Chart.js for visualizations
  * CSS (for styling)
* **Backend**:

  * Node.js
  * Express.js
  * JWT Authentication
  * MongoDB with Mongoose for database management

## Installation

### Prerequisites

* **Node.js** (v14 or higher)
* **MongoDB** (either locally or using a cloud service like MongoDB Atlas)

### Steps to Run the Application

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/expense-management-app.git
   cd expense-management-app
   ```

2. **Install dependencies for the backend**:

   Navigate to the backend directory and run:

   ```bash
   cd backend
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the `backend` folder with the following variables:

   * `MONGODB_URI`: Your MongoDB connection string.
   * `JWT_SECRET`: A secret key for JWT authentication.

4. **Start the backend**:

   In the `backend` directory, run:

   ```bash
   npm start
   ```

   This will start the server at `http://localhost:5000`.

5. **Install dependencies for the frontend**:

   Navigate to the frontend directory and run:

   ```bash
   cd frontend
   npm install
   ```

6. **Start the frontend**:

   In the `frontend` directory, run:

   ```bash
   npm start
   ```

   This will start the React app at `http://localhost:3000`.

7. Open the app in your browser and you should see the expense management application running!


## Folder Structure

```
expense-management-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── styles/
│   └── package.json
│
└── README.md
```

## Contributing

If you would like to contribute to the project, feel free to fork this repository and submit a pull request. Contributions are welcome!

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new pull request.



