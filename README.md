House Painting Business Management System
Overview
Welcome to the House Painting Business Management System! This application is designed to streamline the management of house painting projects, including tracking employee attendance, managing projects, handling payments, and more. The system provides a modern and user-friendly interface, leveraging React for the frontend and Spring Boot for the backend.

Features
User Authentication: Secure login and registration with role-based access control.
Attendance Tracking: Record and manage employee attendance, including presence and absence.
Project Management: Create, update, and manage painting projects with detailed information.
Payment Management: Track and manage payments related to various projects.
Quotation Management: Generate and manage quotations for potential projects.
Feedback Collection: Collect and manage client feedback efficiently.
Labour Management: Manage details of labor and their assignments to projects.
Technologies
Frontend: React.js, Vite
Backend: Spring Boot, Maven
Database: MySQL
Authentication: Keycloak
APIs: RESTful
Styling: Custom CSS for responsive and professional design
Installation
Prerequisites
Java JDK 17+
Node.js 16+
MySQL Database
Backend Setup
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/house-painting-business-management.git
cd house-painting-business-management/backend
Configure the Database

Set up your MySQL database.
Update src/main/resources/application.properties with your database credentials.
Build and Run the Application

bash
Copy code
./mvnw spring-boot:run
Frontend Setup
Navigate to the Frontend Directory

bash
Copy code
cd ../frontend
Install Dependencies

bash
Copy code
npm install
Start the Development Server

bash
Copy code
npm start
API Endpoints
Attendance Management

GET /api/attendances - Retrieve all attendance records
GET /api/attendances/{id} - Retrieve attendance record by ID
POST /api/attendances - Create a new attendance record
PUT /api/attendances/{id} - Update an existing attendance record
DELETE /api/attendances/{id} - Delete an attendance record
Project Management

GET /api/projects - Retrieve all projects
POST /api/projects - Create a new project
PUT /api/projects/{id} - Update an existing project
DELETE /api/projects/{id} - Delete a project
Payment Management

GET /api/payments - Retrieve all payments
POST /api/payments - Create a new payment
PUT /api/payments/{id} - Update an existing payment
DELETE /api/payments/{id} - Delete a payment
Quotation Management

GET /api/quotations - Retrieve all quotations
POST /api/quotations - Create a new quotation
PUT /api/quotations/{id} - Update an existing quotation
DELETE /api/quotations/{id} - Delete a quotation
Usage
Login: Access the application at http://localhost:3000 and log in using your credentials.
Manage Projects: Navigate to the "Projects" section to create and manage projects.
Track Attendance: Go to the "Attendance" section to record and review employee attendance.
Handle Payments: Use the "Payments" section to track and manage payments.
Generate Quotations: Create and manage quotations in the "Quotations" section.
Collect Feedback: View and manage client feedback under the "Feedback" section.
Contributing
We welcome contributions to this project. To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Spring Boot: For providing a robust backend framework.
React: For enabling a dynamic and responsive frontend.
MySQL: For efficient database management.
Keycloak: For secure and flexible authentication.
Contact
For any questions or support, please contact ranjitranju145@gmail.com.
