https://github.com/ShivaniNeharkar/BookBuddy-PERN-stack/assets/43198273/dd9fad9c-77ee-4449-9d3f-cb5505523890




I developed a comprehensive Library Management System using the PERN stack (PostgreSQL, Express, React, and Node.js) to manage both librarian and student roles effectively. Librarians can add, edit, and update book details, while students have the ability to check out, sort, and filter books.

The frontend was built using React with hooks for efficient state management. JWT tokens were used to secure authentication and manage role-based access. The backend leverages PostgreSQL for database management, adhering to an ORM structure for clean and scalable database interaction. I utilized Axios to handle API requests between the frontend and backend.

Additionally, I wrote extensive tests to ensure reliability and maintainability across the application.







# Getting Started with Client and Server
# Login Credentials for Students
  dave@gmail.com
  pwd:  Dave@123

  shivani@gmail.com
   pwd:  Shivani@123

# Login Credentials for Librarian
  librarian@gmail.com
   pwd:  123456

# Prerequisites
Before you begin, ensure you have met the following requirements:

1. Node.js installed
2. npm or yarn package manager installed
3. Setup Instructions


Next step, navigate to server folder

  1. Install npm
     # npm i
     
     
  2. Set up Database
    To create databases, migrate schema, and seed initial data, run the following command:

      # npm run setup-db


  3. Start Server
    To start the server in development mode, use:

      # npm run dev
    This command will start the server at http://localhost:3000 by default.


Next, Navigate to client folder
1. install npm
   # npm i
In a separate terminal or shell, navigate to the client directory and run the following command to start the client application:


# npm start
This command will start the client server and open the application in your default web browser.

Additional Commands
Running Tests
To run tests for the server or client, use the respective commands:

Create a testing database using 

# CREATE DATABASE database_test;

# npm test     



