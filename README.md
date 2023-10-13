# Banking React Application with Node/Express Backend and MySQL Database (AWS Hosting)

## Introduction

This is a comprehensive banking application built with React for the front end, Node.js/Express for the backend, and a MySQL database hosted on AWS. It enables users to perform various banking operations like account management, transactions, and more.

## Features

- User registration and authentication.
- Account creation and management.
- Deposit and withdrawal transactions.
- Balance inquiry and transaction history.
- ...

## Technologies

- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MySQL (AWS RDS)
- **Deployment**: AWS, GitHub Pages

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- Node.js and npm installed for both frontend and backend.
- MySQL client for database access.
- AWS account with the necessary IAM credentials.
- Git for version control.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/banking-app.git
   cd banking-app
   ```

#### Frontend (React)

   ```bash
   cd frontend
   npm install
   ```


#### Backend (Node.js/Express)

```bash
cd backend
npm install
```

Configuration
Set up your AWS RDS instance with a MySQL database and note down the connection details.
Create a .env file in the backend directory and configure the following environment variables:


```bash
env
DB_HOST=your-db-host
DB_USER=your-db-username
DB_PASSWORD=your-db-password
DB_DATABASE=your-db-name
```

### Usage
Start the backend server:

```bash
cd backend
npm start
```

Start the React development server:

```bash
cd frontend
npm start
```

Access the application at http://localhost:3000.

### Testing
To run tests for the backend, use:

```bash
cd backend
npm test
```

To run tests for the frontend, use:

```bash
cd frontend
npm test
```
## Deployment

### Frontend
Deploy the React frontend to GitHub Pages:

```bash
cd frontend
npm run deploy
```
### Backend
Deploy the Node.js/Express backend on your chosen platform (e.g., AWS Elastic Beanstalk, Heroku, etc.).

### Database
The MySQL database is hosted on AWS RDS. Ensure it's properly configured, secured, and backed up.
