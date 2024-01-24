# Test Frontend

## Overview

This is a simple static frontend for the PSQL-Node backend. The frontend consists of HTML files that interact with the backend through API requests.

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd test-frontend
   ```

2. Serve the HTML files locally using `npx serve`:

   ```bash
   npx serve
   ```

   This command will automatically open a server and provide you with a link (usually [http://localhost:5000](http://localhost:5000)).

3. Open your web browser and navigate to the provided link to access the frontend.

## Files:

### 1. new-register.html

This file contains a simple registration form that interacts with the backend's `/register` endpoint. Follow the steps below to use the registration form:

- Open the provided link in your web browser.
- Click on the "Register" link in the navigation or access [http://localhost:5000/new-register.html](http://localhost:5000/new-register.html) directly.
- Fill in the registration form with the required information (Name, Age, Address, Salary, Join Date).
- Click the "Submit" button to send the registration data to the backend.
- Open the browser console to view the response from the backend.

### 2. register.html

This file also contains a registration form that interacts with the backend's `/register` endpoint. Follow the steps below to use the registration form:

- Open the provided link in your web browser.
- Click on the "Register Form" link in the navigation or access [http://localhost:5000/register.html](http://localhost:5000/register.html) directly.
- Fill in the registration form with the required information (Name, Age, Address, Salary, Join Date).
- Click the "Submit" button to send the registration data to the backend.

### 3. showall.html

This file provides a button to fetch and display all data from the backend's `/showall` endpoint. Follow the steps below to use the "Show Data" feature:

- Open the provided link in your web browser.
- Click on the "Show All Data" link in the navigation or access [http://localhost:5000/showall.html](http://localhost:5000/showall.html) directly.
- Click the "Show Data" button to fetch and display all data from the backend.

### 4. URLS.js

This file contains the backend URL (`BACKEND_URL`) used by the frontend to communicate with the PSQL-Node backend. Ensure that the URL is correctly configured before using the frontend files.

Feel free to explore and modify the HTML files as needed for your application.

---