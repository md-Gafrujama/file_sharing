# MERN Stack File Sharing Application

This is a **File Sharing Application** built using the **MERN stack** (MongoDB, Express.js, React, and Node.js). It allows users to upload, view, and download files from the platform.

## Features

- **File Upload**: Users can upload files of various types (e.g., images, PDFs, documents).
- **File Download**: Users can download the files that have been uploaded.
- **File Viewing**: Users can view the list of uploaded files.
- **Admin Panel**: Admins have access to delete files.

## Tech Stack

### Frontend:
- **React**: Handles the user interface and communicates with the backend API for file operations.
- **Axios**: Used for making HTTP requests to the backend.
- **Bootstrap**: For styling and responsiveness.

### Backend:
- **Node.js**: JavaScript runtime to handle server-side logic.
- **Express.js**: Web framework for Node.js to build APIs.
- **Multer**: Middleware to handle file uploads.
- **MongoDB**: NoSQL database for storing file metadata.
- **Mongoose**: ODM for MongoDB to interact with the database.

## Project Structure


### Backend

- **controllers**: Contains logic for handling requests (file upload, file retrieval, deletion).
- **models**: Defines the schema for file metadata using Mongoose.
- **routes**: Defines the API routes (e.g., `/upload`, `/files`, `/delete`).
- **uploads**: Directory where the uploaded files are temporarily stored.
- **server.js**: Main server file that sets up Express and connects to MongoDB.

### Frontend

- **App.js**: Main React component that handles routing and rendering of file upload/download features.
- **components**: Contains reusable UI components (e.g., FileUpload, FileList, FileDownload).

## Prerequisites

Make sure you have the following installed:

- **Node.js**: >= 12.x
- **MongoDB**: >= 4.x

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/file-sharing-app.git
cd file-sharing-app/backend
npm install
cd ../frontend
npm install
cd ../frontend
npm install
MONGO_URI=mongodb://localhost:27017/fileSharingDB
cd backend
npm start

cd ../frontend
npm start
