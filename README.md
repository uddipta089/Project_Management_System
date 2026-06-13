# Project Management System

A full-stack project management system built using Node.js, Express.js, and MongoDB for efficient task tracking and team collaboration.

## Features

- Create and manage projects
- Assign tasks to team members
- Track task progress and status
- Update and delete projects and tasks
- RESTful API architecture
- Secure environment variable management using dotenv

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- Dotenv

## Project Structure

```
project-management-system/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
├── package.json
└── package-lock.json
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/uddipta089/Project_Management_System.git
```

2. Navigate to the project folder

```bash
cd Project_Management_System
```

3. Install dependencies

```bash
npm install
```

4. Create a `.env` file

```env
MONGODB_URI=your_mongodb_connection_string
PORT=8000
```

5. Start the application

```bash
npm start
```

## API Endpoints

### Projects
- `POST /api/projects`
- `GET /api/projects`
- `PUT /api/projects/:id`
- `DELETE /api/projects/:id`

### Tasks
- `POST /api/tasks`
- `GET /api/tasks`
- `PUT /api/tasks/:id`
- `DELETE /api/tasks/:id`

### Users
- `POST /api/users`
- `GET /api/users`
- `PUT /api/users/:id`
- `DELETE /api/users/:id`

## Future Enhancements

- JWT Authentication
- Role-Based Access Control
- Email Notifications
- File Attachments
- Analytics Dashboard

## Author

**Uddipta Pathak**

- GitHub: https://github.com/uddipta089
- LinkedIn: https://www.linkedin.com/in/uddipta-pathak/

---
