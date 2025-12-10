# personal-finance-tracker-web
The Personal Finance Tracker is a full-stack web application designed to help users manage their daily financial activities with ease. 
A simple and clean full-stack web application to track income, expenses, categories, and monthly spending patterns. Built using the MERN stack with secure authentication and responsive UI.

Features

User signup/login with JWT

Add, edit, delete income and expenses

Category-wise tracking

Monthly analytics with charts

Export data to CSV

Responsive React UI

Tech Stack

Frontend: React, Axios, Chart.js
Backend: Node.js, Express.js, JWT
Database: MongoDB / Mongoose

Project Structure
client/     → React frontend
server/     → Node + Express backend
README.md

Setup
Backend
cd server
npm install
npm start

Frontend
cd client
npm install
npm start


Frontend: http://localhost:3000

Backend: http://localhost:5000

Endpoints

POST /auth/register

POST /auth/login

GET/POST/PUT/DELETE /transactions
