
# Jobseeker Application

## About the Project

The Jobseeker Application is a comprehensive platform designed to connect jobseekers and employers. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js), this application streamlines the job application process and job vacancy management.

### Key Features

#### For Jobseekers:
- **Apply for Jobs**: Search and apply for job openings with ease.
- **Update Resume**: Upload and update your resume to enhance your profile.
- **Manage Profile**: Edit personal information, track application status, and view past applications.

#### For Employees:
- **Create Job Vacancies**: Post new job opportunities to attract potential candidates.
- **View Resumes**: Access and review resumes of jobseekers who have applied for job listings.

## Technologies Used

- **MongoDB**: A NoSQL database used to store user data, job listings, and resumes.
- **Express.js**: A web application framework for Node.js that handles routing and server-side logic.
- **React.js**: A front-end library for building dynamic user interfaces.
- **Node.js**: A JavaScript runtime used to build the server-side application.

## Setup

### Prerequisites
- Node.js and npm installed.
- MongoDB server running.

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/kartik0209/jobseeker.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd jobseeker
   ```

3. **Install Dependencies**

   For the server:
   ```bash
   cd server
   npm install
   ```

   For the client:
   ```bash
   cd ../client
   npm install
   ```

4. **Setup Environment Variables**

   Create a `.env` file in the `server` directory and add the following variables:

   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

   Replace `your_mongodb_connection_string` and `your_jwt_secret` with your actual MongoDB URI and JWT secret.

5. **Start the Application**

   Start the server:
   ```bash
   cd server
   npm start
   ```

   Start the client:
   ```bash
   cd ../client
   npm start
   ```

   The server will be running on `http://localhost:5000` and the client on `http://localhost:3000`.

## Usage

- **Jobseekers**: Visit the client application to apply for jobs, update your resume, and manage your profile.
- **Employees**: Use the employee dashboard to create job vacancies and view resumes.

