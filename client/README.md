
Task Management System
This project is a task management system built using the MERN stack (MongoDB, Express.js, React, Node.js) along with Redux for state management. The system allows users to manage their tasks, create new tasks, update task statuses, and more.


Features
User Authentication: Allows users to sign up, log in, and manage their accounts securely.
Task Creation: Users can create new tasks 
Task Status Updates: Ability to mark tasks as completed, pending, or in progress.
Search and Filter: Provides search and filter options to quickly find tasks based on various criteria.
Dashboard View: Overview of tasks, categorized and organized for better management.
Responsive Design: Ensures seamless usage across various devices and screen sizes.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/shameemfrhn/task-management-system.git
cd task-management-system
Install Dependencies:

bash
Copy code
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
Set Environment Variables:

Create a .env file in the /server directory and set environment variables like PORT, MONGODB_URI, and JWT_SECRET.
Run the Application:

bash
Copy code
# Start the server (from /server directory)
npm start

# Start the client (from /client directory)
npm start
Technologies Used
Frontend: React, Redux, HTML, CSS, JavaScript
Backend: Node.js, Express.js, MongoDB
State Management: Redux
Authentication: JSON Web Tokens (JWT)
Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements, bug fixes, or new features.

License
This project is licensed under the MIT License.

