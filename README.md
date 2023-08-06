# PATIENT DATA FILING
    ABOUT
The LONGANI- Patient Data Storage and Management Program aims to develop a comprehensive software solution that addresses the challenges of manual processes and limited access to patient data in government healthcare facilities. It seeks to provide healthcare professionals with easy access to accurate and up-to-date patient information, improving the quality of care and enhancing decision-making.

The Hospital Patient Register Application was built with React and Express, using MongoDB as the database and Mongoose as the ORM. The application allows patients to register using their names and IDs, and it enables users(health personnel) to retrieve the list of registered patients along with their visit history and associated doctors.

    EXACT SETUP
     The initial steps are: 

Prerequisites

Before setting up the project, make sure you have the following installed on your machine:

Node.js and npm - To run the server and frontend.
MongoDB - To set up the database.
Getting Started

Follow these steps to get the project up and running:

Step 1: Clone the Repository - git clone https://github.com/Cecilia-Banda/LONGANI--Data-Project.git

Step 2: Install Dependencies

Navigate to the root folder of the project and install the necessary dependencies for both the backend and frontend:
    install npm
Step 3: Set up the Database

Ensure you have MongoDB installed and running on your machine. Create a new database for this project. By default, the backend server connects to MongoDB at mongodb://localhost/hospital-register. If you want to use a different MongoDB URI, update it in the backend/config/db.js.

Step 4: Configure Environment Variables

Rename the .env.example to .env in the backend folder and update the environment variables if needed.

Step 5: Run the Application

Now, start the backend server and frontend development server separately. Open two terminals:

Terminal 1 - Backend Server :
cd backend
npm start
Terminal 2 - Frontend Development Server

cd frontend
npm start
Step 6: Access the Application

Once both the backend server and frontend development server are running, you can access the application in your browser https://longani-data-project.vercel.app/

Usage

To register a new patient, use the POST request to /api/patients with patient details (name, ID, etc.).

