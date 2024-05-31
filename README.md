# Market Dashboard and Predictor

This project is a market dashboard and predictor that provides users with portfolio management, market data, and top mutual fund information. It is built using React, Flask, MySQL, and the Yahoo Finance API.

## Features

- **Market Dashboard**: View real-time market data and trends.
- **User Portfolio Management**: Manage and track your investments.
- **Market Data Fetching**: Retrieve the latest market data from the Yahoo Finance API.
- **Top Mutual Fund Information**: Get information on top mutual funds.

## Technologies Used

- **Frontend**: React
- **Backend**: Flask
- **Database**: MySQL
- **Data Source**: Yahoo Finance API

## Setup

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js and npm
- Python and pip
- MySQL

### Installation



1. **Frontend Setup:**

    Navigate to the `frontend` directory and install the dependencies:

    ```bash
    cd frontend
    npm install
    ```

2. **Backend Setup:**

    Navigate to the `backend` directory and install the dependencies:

    ```bash
    cd ../backend
    pip install flask
    ```


3. **Environment Variables:**

    Create a `.env` file in the `backend` directory and add your MySQL database configuration:

    ```plaintext
    MYSQL_USER=your_mysql_username
    MYSQL_PASSWORD=your_mysql_password
    MYSQL_DB=market_dashboard
    MYSQL_HOST=localhost
    ```

4. **Running the Development Servers:**

    - **Frontend (React):**

      ```bash
      cd frontend
      npm start
      ```

    - **Backend (Flask):**

      ```bash
      cd ../backend
      python/python3 app.py
      ```


