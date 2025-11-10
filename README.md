Hospital Management System

This is a full-stack Hospital Management System built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
It provides a simple interface to manage doctors, patients, and appointment scheduling.

Features:
 1. Add, view, and delete doctors
 2. Add, view, and delete patients
 3. Schedule appointments by selecting a doctor and patient
 4. Dropdowns automatically update when new doctors or patients are added
 5. If a doctor or patient is removed later, existing appointments remain and display "Unavailable" instead of breaking
 6. Clean and organized user interface for easy navigation

Technologies Used:
 Frontend: React.js
 Backend: Node.js and Express.js
 Database: MongoDB with Mongoose
 Styling: CSS

How to Run the Project:
Start the Backend:
cd backend
npm install
node server.js

Make sure MongoDB is running.

Start the Frontend:
cd frontend
npm install
npm start

Frontend will run on: http://localhost:3000
Backend will run on: http://localhost:5000
