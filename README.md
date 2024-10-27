# Task_Backend_VE3
## This Backend was Push on GitHub
## https://github.com/Balajibalu19/VE3_Backend.git



# Features
1. Task Management: Create, edit, delete, and view tasks.
2. Simple Authentication: Basic login and registration without JWT.
3. Responsive Design: Adaptable UI for desktop and mobile devices.
4. Error Handling: Handles incorrect routes and invalid data entries.



# Backend
1. Framework: Node.js with Express
2. Database: MongoDB (via Mongoose)
3. Authentication: Simple session-based authentication
4. Environment Management: dotenv 


Backend Setup
1. Clone the repository and navigate to the backend directory:

git clone 
## https://github.com/Balajibalu19/VE3_Backend.git
cd task-manager-backend
Install dependencies:


2. npm install
Create an .env file in the root of the backend directory and add the following variables:

PORT=5000
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret

3. # Run the backend server:
node functions/api.js


Test the API at http://localhost:5000/api.




The backend API provides RESTful endpoints for managing tasks and basic user authentication.

# Endpoints
# Tasks

Method	Endpoint	Description
GET	/tasks	Fetch all tasks
GET	/tasks/:id	Fetch a single task by ID
POST	/tasks	Add a new task
PUT	/tasks/:id	Update a task by ID
DELETE	/tasks/:id	Delete a task by ID


# Authentication
Method	Endpoint	Description
POST	/auth/register	Register a new user
POST	/auth/login	Login with email and password
GET	/auth/logout	Logout the user
