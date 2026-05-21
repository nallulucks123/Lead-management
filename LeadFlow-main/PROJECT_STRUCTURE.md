# Project Structure Documentation


## Architecture Overview

This project follows a **full-stack React + Node.js architecture** with:

- **Frontend**: React 18 with Vite, Tailwind CSS, and shadcn/ui components
- **State Management**: Redux Toolkit for global state
- **Backend**: Node.js with Express.js REST API
- **Database**: Configured through db.js (MongoDB)
- **Authentication**: JWT-based auth with protected routes
- **Styling**: Tailwind CSS with custom theme configuration

## Key Design Patterns

- **Feature-based organization** for scalable code structure
- **Component composition** with reusable UI elements
- **Separation of concerns** between controllers, models, and routes
- **Context API** for global application state
- **Middleware pattern** for authentication and authorization
