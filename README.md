# Project Example CRUD Product

A full-stack web application built with Go backend and React frontend framework.

## Tech Stack

- **Backend**: Go Echo
- **Frontend**: React Typescript with Vite and Tailwinds CSS
- **Database**: MongoDB Community Server

## Installation

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [MongoDB Community Server](https://www.mongodb.com/try/download/community)
- [Go](https://golang.org/dl/) (latest version recommended)
- [Node.js](https://nodejs.org/) (includes npm)

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/TheJrnyDev/crud-product.git
```

2. **Install backend dependencies**
```bash
cd backend
go mod tidy
```

3. **Install frontend dependencies**
```bash
cd frontend
npm install
```

## Running the Application

1. **Start the backend server (default port is 8080)**
```bash
go run main.go
```

2. **Start the frontend development server (default port is 5137)**
```bash
npm run dev
```

3. **Access the application**
- Frontend: http://localhost:5137
- Backend API: http://localhost:8080

## Environment Configuration

The project uses environment variables for configuration. We have `.env` file in the backend directory with the following variables:

- `MONGODB_URI`: MongoDB connection string
- `DATABASE_NAME`: Name of the database to use
- `PORT`: Port for the backend server

## Project Structure

```
crud-product/
├── backend/
│   ├── config/
│   │   └── database.go
│   ├── .env
│   ├── go.mod
│   └── main.go
|   └── ...
├── frontend/
│   ├── package.json
│   └── ...
└── README.md
```

## Learning Outcomes

This project served as a practical learning experience in modern software development practices:

- **Microservices Architecture**: Successfully applied microservices design patterns to create scalable and maintainable services
- **Clean Architecture**: Implemented clean architecture principles for better code organization and separation of concerns
- **Full-Stack Development**: Gained hands-on experience integrating Go backend with modern frontend technologies
- **Database Integration**: Learned to work with MongoDB in a production-like environment

## Contact

Kittipong Piada - kittipongpiada@gmail.com
