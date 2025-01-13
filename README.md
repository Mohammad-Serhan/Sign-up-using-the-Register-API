# Customer Registration and Admin Management System
## Overview
##### This project is a full-stack application featuring a React.js frontend and an Express.js backend. It allows customers to register, while administrators can log in, manage customer data, and view statistical insights. The application includes a responsive design, JWT-based authentication, and RESTful APIs to deliver a robust and scalable solution.

## Frontend
### React.js Framework

#### Setup Instructions
1. Navigate to the front-end folder:

    `cd front-end`.
2. Install dependencies:

    `npm install`.
3. Run the application:
    `npm start`.
4. Access the application in your browser at `http://localhost:3000`.
 
#### Features
* Landing Page:
    * Navigate to / to view the design page based on the provided layout.
* Admin Login:
    * Access /admin/login for admin login.
    * Successful login generates a JWT token, which is stored on the client side for secure authentication.
* Customer Signup:
    * Use /customers/signup to allow customers to register.
* Customer Management:
    * Navigate to /customers to:
        * View all registered customers.
        * Use pagination to display 20, 40, or 60 customers per page.
        * Filter customers by ID, first name, or email.
* Registration Statistics:
    * Access aggregated data showing the average number of registrations over a specific period:
        * Last 24 hours
        * Last week
        * Last month
        * Last 3 months
        * Last year
* Additional Route
    * Design Preview:
        * Visit `/design` to view a PDF file showcasing the application's wireframe or design documentation.


## Backend

### Express.js Framework

#### Setup Instructions
1. Navigate to the back-end folder:

    `cd back-end`.
2. Install dependencies:

    `npm install`.
3. Run the server:

    `npm start`.
4. API base URL: `http://localhost:8080`.

#### APIs Implemented
1. Login API:
    * Allows admin users to log in using JWT authentication.
2. Logout API:
    * Handles secure logout for admin users.
3. Register API:
    * Adds new customer records.
4. Customers API:
    * Retrieves a paginated list of customers with filtering options (ID, first name, email).
5. Average API:
    * Calculates the average number of customer registrations over customizable time periods.
    

### Features Summary
* Frontend: Developed using React.js with a responsive design.
* Backend: Built using Express.js with secure and scalable RESTful APIs.
* Authentication: JWT-based authentication for secure login sessions.
* Statistics: Real-time data aggregation for registration insights.
* Design Documentation: Available at /design route.


### Technologies Used
* Frontend: React.js
* Backend: Express.js
* Database: MongoDB or MariaDB (MySQL)
* Authentication: JWT
* Other Tools: Node.js, RESTful APIs
