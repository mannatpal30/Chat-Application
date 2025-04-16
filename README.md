Chat App

A modern real-time chat application built with MERN stack, featuring authentication, theming, real-time messaging using Socket.io, and a clean, responsive UI.

🚀 Features

User authentication (signup/login/logout)

Real-time chat with Socket.io

Light/Dark mode support

Responsive design

Global state management using Zustand

Protected routes

Modular architecture

🛠️ Tech Stack

Frontend:

React + Vite

Zustand for state managemen

TailwindCSS

Axios

Backend:

Node.js

Express.js

MongoDB + Mongoose

Socket.io

JWT Authentication

Setup & Run Locally:
Prerequisites

Node.js

MongoDB

Git

Backend......

cd backend

npm install

npm run dev


Create a .env file inside backend/:

PORT=5000

MONGO_URI=your_mongo_connection_string

JWT_SECRET=your_secret_key

Frontend......

cd frontend

npm install

npm run dev

📁 Folder Structure 

/frontend
  /src
    /components
    /store
    /lib
    /constants

/backend
  /src
    /controllers
    /routes
    /middlewares
    /models





