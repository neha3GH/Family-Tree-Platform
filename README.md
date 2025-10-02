Kulvansh Project - Backend and Frontend Integration
Overview
This project is a web-based platform designed to facilitate family tree registration and creation. The system consists of two key forms:
Kulvansh Registration Form - Collects user details and payment information.
Family Tree Details Form - Captures family relationship data to generate a structured family tree.
The backend is being developed using Node.js, with MongoDB for user data storage and Neo4j for managing family tree relationships. The frontend has been built using WordPress for the Kulvansh website and Glitch for the frontend coding, with the code written in HTML, CSS, and JavaScript.

System Requirements
Before running the project, ensure that the following dependencies are installed on your system:
Node.js (Latest stable version)
MongoDB (For user data storage)
Neo4j (For managing family tree relationships)
Express.js (For backend API handling)

Installation & Setup
1. Install Node.js and Required Packages
Download and install Node.js from nodejs.org
Navigate to the backend directory in the terminal and run:
npm install
This will install all required dependencies such as express, mongoose, neo4j-driver, body-parser, and cors.
2. Set Up MongoDB
Ensure that MongoDB is installed and running locally.
If using MongoDB locally, start it by running:
mongod
The database connection URI is configured inside config.js.
3. Set Up Neo4j
Install Neo4j from neo4j.com
Start the Neo4j database and open Neo4j Browser at http://localhost:7474
The connection credentials are configured in the backend code.
4. Run the Backend Server
Navigate to the backend directory and execute:
node server.js
The server should start and run at http://localhost:8080.

Running the Frontend
The frontend consists of an HTML-based interface.
Open index.html in a web browser.
The forms for registration and family tree input will be displayed.
Once data is submitted, it will be processed by the backend.

Troubleshooting
Issue: Unable to connect to MongoDB
Solution: Ensure MongoDB service is running using mongod.
Issue: Neo4j connection errors
Solution: Verify that Neo4j is running and credentials are correct.
Issue: Backend not responding
Solution: Check if Node.js server is running on the correct port.

Additional Notes
The Kulvansh Registration Form requires users to upload payment proof.
Data is stored in MongoDB, and family relationships are managed in Neo4j.

For any clarifications, please feel free to reach out.
Prepared by: Neha M
Email: nehaneya342@gmail.com
Contact: +91 7483686554
