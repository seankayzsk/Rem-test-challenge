# Rem-test-challenge
Automated testing
# REM Waste QA Automation Challenge

## Overview

This project is a web application with a React frontend and Node.js backend API, designed to demonstrate functional UI and API test automation.

---

### Application folder Structure 

backend/
server.js
package.json

frontend/
src/
App.js
package.json

tests/
api/
api.test.js
ui/
login.spec.js
package.json

## Setup Instructions

### Prerequisites

- Node.js (v14+ recommended)
- npm (comes with Node.js)

---------------------------------------------------------

### Backend Setup

1. Open terminal and navigate to the `backend` directory:
cd backend

2. Install dependencies:
npm install

3. Start the backend server:
node server.js

4. The backend API will run on:  
`http://localhost:5000`

----------------------------------------------------------

### Frontend Setup

1. Open another terminal and navigate to the `frontend` directory:
cd frontend

2. Install dependencies:
npm install

3. Start the React app:
npm start

4. The app will open in your browser at:  
`http://localhost:3000`

------------------------------------------------------------

### Running Tests

#### API Tests

1. Navigate to the `tests` directory:
cd tests

2. Install dependencies:
npm install

3. Run API tests with Jest and Supertest:
npm run test:api

#### UI Tests

1. From the `tests` directory, run Cypress UI tests:
npm run test:ui

--------------------------------------------------------

### Credentials for Login

- **Username:** admin
- **Password:** password

---

### Notes

- Backend uses a simple token-based authentication for demo purposes.
- All data is stored in-memory (no database).
- Tests cover login, CRUD operations on items, and both positive/negative cases.

---




