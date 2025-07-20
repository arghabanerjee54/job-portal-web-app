# Job Portal Application

This is a full-stack job portal application that allows users to search, apply, and manage job postings. It includes both a frontend built with React and Vite, and a backend built with Node.js and Express.

## Features

### Frontend
- Built with React and Vite.
- State management using Redux Toolkit.
- Tailwind CSS for styling.
- User authentication and role-based access control.
- Job search and filtering.
- Admin dashboard for managing companies and job postings.
- Responsive design.

### Backend
- Built with Node.js and Express.
- MongoDB as the database.
- Authentication using JWT.
- File uploads using Multer and Cloudinary.
- RESTful APIs for user, company, job, and application management.

---

## Project Structure
jobportal-yt-main/
├── backend/                     # Backend server
│   ├── controllers/            # API controllers
│   ├── middlewares/            # Middleware functions
│   ├── models/                 # Mongoose models (MongoDB schema)
│   ├── routes/                 # Express API routes
│   ├── utils/                  # Utility/helper functions
│   ├── index.js                # Backend entry point
│   └── package.json            # Backend dependencies & scripts
│
├── frontend/                   # Frontend client (React + Vite)
│   ├── public/                 # Static assets (favicon, images, etc.)
│   ├── src/                    # Main source code (components, pages, etc.)
│   ├── index.html              # HTML entry file
│   ├── package.json            # Frontend dependencies & scripts
│   └── vite.config.js          # Vite configuration file
│
└── README.md                   # Project documentation


---

## Installation

### Prerequisites
- Node.js (v16 or higher)
- MongoDB
- Cloudinary account for file uploads
