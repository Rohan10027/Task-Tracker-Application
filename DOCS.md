Task Tracker Application link: (https://rebrand.ly/pl2giqc) // here I am able to link with frontend with backend. Further it takes some time to do.
=======================

**************************************Full-Stack-Assignment: Task Tracker Application*********************************

Objective:
Your objective is to create a Task Tracker Application using Java/ Spring Boot for the
backend and ReactJS for the frontend. The application should provide users with the
ability to manage their tasks, including creating, updating, deleting, and marking tasks as
completed.

Requirements:
Backend (Java/Spring Boot):
- Create a Java project and set up a virtual environment.
- Design a model for tasks with fields such as title, description, due_date, and
completed.
- Set up RESTful API endpoints for CRUD operations on tasks.
- Implement a robust validation mechanism to ensure data integrity.
- Implement error handling, providing clear and informative error messages.
- Implement pagination for task retrieval to optimise performance as the number of
tasks grows.
- Implement user authentication using Spring Security for secure task
management.
- Utilise a database of your choice MongoDB to store task
information.
- Implement a comprehensive logging system to track critical events and errors.

Frontend (HTML/CSS/JavaScript or ReactJS):
Set up a project using the specified tools.
Create components for the following:
- Task list display
- Task creation
- Task editing
- Fetch tasks from the backend API and display them in a paginated list.
- Implement functionality to create, edit, and delete tasks with proper error
handling.
- Implement the ability to mark tasks as completed.
- Style the application for an intuitive and user-friendly interface.

Integration:
- Connect the frontend and backend to enable real-time communication.
- Utilise WebSocket or Socket.io to handle messaging between clients and the

Tomcat server.
- Implement appropriate HTTP methods for user authentication (if applicable).
- Which listens for HTTP requests on port 8080.


****************************************SOLUTION:**************************************************

Frontend (ReactJS):
1. Project Setup:
   Use Create React App or a similar tool to set up your React project.
   
2. Components:
   Create React components for task list display, task creation, and task editing.
   
3. Fetch Tasks from Backend API:
   Use the fetch API or a library like Axios to retrieve tasks from your backend.
   Display the tasks in a paginated list.

4. Task Operations:
Implement functionality to create, edit, and delete tasks.
Handle errors gracefully and provide feedback to the user.
Mark Tasks as Completed:

Add a feature to mark tasks as completed and update the backend accordingly.
User Interface Styling:

Style your components for a user-friendly interface.
Consider using a CSS framework like Bootstrap or styled-components.
Integration:
Connect Frontend and Backend:

Ensure that your React frontend can make HTTP requests to the Spring Boot backend.
Use the appropriate API endpoints in your frontend components.
Real-time Communication:

Implement WebSocket or Socket.io for real-time communication if needed.
For this task tracker application, it might be optional unless you want real-time updates.
User Authentication:

Use appropriate HTTP methods (e.g., POST for login) to handle user authentication.
Port Configuration:

Ensure your Spring Boot backend listens for HTTP requests on port 8080.



For Running Locally:
localhost:8080/ (port = 8080)
mongodb port 27017
### Configuration
1. Default app port: **8080**
2. Default server host:port: **8080**
3. Default ui port: **3000**
4. *\main\resources\application.properties*:
5. Install mongodb
6. Integration tests are using embedded mondgodb: **de.flapdoodle.embed.mongo**
7. For application to work properly start mongodb on **localhost:27017**

| Property                 | Description                        | Default    |
| ------------------------ | ---------------------------------- | ---------- |
| spring.profiles.active   | Active spring profiles             | production |
| spring.data.mongodb.host | Mongo DB host                      | localhost  |
| spring.data.mongodb.port | Mongo DB port                      | 27017      |
| todolist.dbname          | Application dbname within Mongo DB | tasks      |

### Dependencies / Libs

* **Language**: Java 8 / Javascript (ECMA6, JSX syntax)
* **Main App Libs**: Java: Spring (Spring Boot, MVC), React
* **Build Tools**: Gradle, npm, webpack, babel, eslint

### Dev Environment
1. General: windows 7 64bit, jdk 1.8, node v4.5.0, npm 2.15.9, gradle 2.14.1 (gradle wrapper available)
2. Mongo DB version v3.2.9

