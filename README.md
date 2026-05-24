# Task Management Application

A full-stack task management web application that allows users to create, update, organize, and track tasks efficiently. The application supports user authentication, task CRUD operations, responsive UI, and optional real-time updates.

---

## Features

- User Authentication & Authorization
- Create, Read, Update, Delete (CRUD) Tasks
- Task Status Tracking
- Responsive Design for Mobile & Desktop
- Secure API Integration
- Dynamic Data Handling
- Optional Real-Time Updates using WebSockets

---

## Tech Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- JWT (JSON Web Token)
- bcrypt.js

### Optional
- Socket.IO for Real-Time Updates

---

## Project Structure

```bash
task-management-app/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── README.md
└── package.json
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/task-management-app.git
```

### Navigate to Project Directory

```bash
cd task-management-app
```

---

## Backend Setup

```bash
cd server
npm install
```

### Create `.env` File

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

### Run Backend

```bash
npm start
```

---

## Frontend Setup

```bash
cd client
npm install
npm start
```

---

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register User |
| POST | `/api/auth/login` | Login User |

### Tasks

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/tasks` | Get All Tasks |
| POST | `/api/tasks` | Create Task |
| PUT | `/api/tasks/:id` | Update Task |
| DELETE | `/api/tasks/:id` | Delete Task |

---

## Task Features

- Add New Tasks
- Edit Existing Tasks
- Delete Tasks
- Mark Tasks as Completed
- Filter Tasks by Status
- Search Tasks

---

## Responsive Design

The application is optimized for:

- Desktop Screens
- Tablets
- Mobile Devices

---

## Optional Real-Time Features

Using Socket.IO:

- Live Task Updates
- Instant Changes Across Users
- Real-Time Notifications

---

## Learning Outcomes

Through this project, you will learn:

- Full-Stack Web Development
- REST API Development
- Authentication & Authorization
- Database Integration
- State Management
- Frontend-Backend Communication
- Responsive Web Design
- Dynamic Data Handling

---

## Future Enhancements

- Dark Mode
- Drag & Drop Tasks
- Team Collaboration
- Notifications
- Task Categories & Tags
- Calendar Integration

---

## Author

Bhavani H

---

## License

This project is licensed under the MIT License.
