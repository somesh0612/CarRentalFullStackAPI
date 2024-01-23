# CarRentalFullStackAPI



CarRental is a FullStack web application for managing car rental services. It allows users to browse available cars, register, and log in. Admins can approve or reject cars for rental.

## Features

- User Authentication: Users can register, log in, and log out.
- Car Management: Admins can view all cars, approve or reject them for rental.
- Responsive Design: The application is designed to work seamlessly on various devices.

## Tech Stack

- **Frontend:**
  - HTML, CSS, JavaScript
  - Bootstrap for styling
  - JavaServer Pages (JSP) for dynamic web pages

- **Backend:**
  - Java Servlets
  - JDBC for database connectivity

- **Database:**
  - MySQL for data storage

## Setup

1. **Database Setup:**
   - Install MySQL and create a database named `carrental`.
   - Import the provided SQL script (`carrental.sql`) to set up the necessary tables.

2. **Backend Setup:**
   - Open the backend project in your preferred IDE.
   - Configure database credentials in the `DBConnector` class.
   - Run the backend server.

3. **Frontend Setup:**
   - Open the frontend project in your preferred code editor.
   - Modify the database connection parameters in the relevant files if needed.
   - Deploy the frontend on a web server or run it locally.

4. **Accessing the Application:**
   - Open a web browser and navigate to `http://localhost:your-port`.

## Usage

1. **User Registration:**
   - Users can register for a new account using the registration page.

2. **User Login:**
   - Registered users can log in to their accounts using the login page.

3. **Car Browsing:**
   - Users can browse the available cars without logging in.

4. **Admin Approval:**
   - Admins can log in and approve or reject cars for rental.

