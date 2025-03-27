# HireHub ( Job Portal )

## Overview
This project is a full-stack web application designed to serve as a HireHub where employers can post job listings and job seekers can browse and apply for jobs. The application is built using React.js for the frontend, Express.js for the backend, and MongoDB as the database.

## Features
### For Job Seekers
<b>Browse Jobs:</b> View a list of available job postings.

<b>Search and Filter:</b> Search for jobs by title, location, or company, and filter by job type, salary range, etc.

<b>Apply for Jobs:</b> Submit applications for jobs directly through the portal.

<b>User Profile:</b> Create and manage a personal profile, including resume upload and contact information.

### For Employers
<b>Post Jobs:</b> Create and publish new job listings.

<b>Manage Listings:</b> Edit or delete existing job postings.

<b>View Applications:</b> See a list of applicants for each job posting.

<b>Company Profile:</b> Create and manage a company profile.

### Technologies Used
<b>Frontend:</b> React.js, React Router, Axios, Bootstrap/Material-UI

<b>Backend:</b> Express.js, Node.js

<b>Database:</b> MongoDB, Mongoose

<b>Authentication:</b> JSON Web Tokens (JWT)

<b>Other Tools:</b> Babel, Webpack, NPM/Yarn

## Getting Started
### Prerequisites
Node.js and npm installed on your machine.

MongoDB installed and running.

Installation
Clone the repository

bash
git clone https://github.com/rahul-rathee7/HireHub.git
cd HireHub
Install dependencies

Navigate to both the client and server directories and install the necessary dependencies.

bash
cd frontend
npm install

## Set up environment variables

Start the server and the client.

bash
cd backend
node index.js

The React application will run on http://localhost:5173 and the Express server on http://localhost:8000.

## Project Structure

job-portal/
│
├── frontend/                  # Frontend React application
│   ├── public/              # Static assets
│   ├── src/                 # React components, pages, and utilities
│   └── package.json         # Frontend dependencies
│
├── backend/                  # Backend Express application
│   ├── config/              # Configuration files (e.g., database connection)
│   ├── controllers/         # Route controllers
│   ├── models/              # Mongoose models
│   ├── routes/              # API routes
│   ├── middleware/          # Custom middleware (e.g., authentication)
│   └── package.json         # Backend dependencies
│
└── README.md                # This file

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments
Hat tip to anyone whose code was used

Contact
For any inquiries, please reach out to ratheerahul602@gmail.com.
