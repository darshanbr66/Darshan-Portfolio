MERN Portfolio Website
A modern, high-tech personal portfolio website built with the MERN stack (MongoDB, Express, React, Node.js) using Vite for the frontend.
Setup Instructions
Prerequisites

Node.js
MongoDB
npm

Backend Setup

Navigate to the server directory:cd server
Install dependencies:npm install
Create a .env file with your MongoDB URI:MONGO_URI=mongodb://localhost:27017/portfolioPORT=5000
Start the server:npm start

Frontend Setup

Navigate to the client directory:cd client
Install dependencies:npm install
Set up Tailwind CSS:npm install -D tailwindcss postcss autoprefixernpx tailwindcss init -p
Start the Vite development server:npm run dev

Notes

Replace profile.jpg in client/src/assets/ with your actual profile picture.
Update the resume link in About.jsx.
Add project data to MongoDB via the /api/projects endpoint (e.g., using Postman).
The site uses Tailwind CSS for styling, Framer Motion for navbar animations, and AOS for scroll animations.

Features

Dark theme with glassmorphism and neon effects
Responsive design
SEO optimized
MongoDB-backed projects and contact form
Smooth scroll animations
