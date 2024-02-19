This project is a simple To-Do list application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create, read, update, and delete tasks.

Table of Contents
Demo
Features
Installation
Usage
Technologies Used
Contributing
License
Demo
[Insert Demo Link Here]

Features
Create a new task
Mark a task as completed
Edit an existing task
Delete a task
Filter tasks by status (completed, active)
Responsive design for mobile and desktop
Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repo.git
Install dependencies in both the client and server directories:

bash
Copy code
cd client
npm install
cd ../server
npm install
Create a .env file in the server directory and add your MongoDB connection string:

env
Copy code
MONGODB_URI=your_mongodb_connection_string
Start the server:

bash
Copy code
cd ../server
npm start
Start the client:

bash
Copy code
cd ../client
npm start
Open your browser and go to http://localhost:3000 to view the application.

Usage
Add a new task by typing in the input field at the top and pressing Enter.
Click on a task to mark it as completed.
Double click on a task to edit its content.
Click on the trash icon to delete a task.
Use the filter buttons at the top to view only completed or active tasks.
Technologies Used
MongoDB
Express.js
React.js
Node.js
HTML/CSS
JavaScript
Bootstrap (optional)
Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License.
