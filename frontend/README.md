💬 Zync - A Real-Time Chat Application
<p align="center">
<img src="https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge" alt="Version">
<img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
<img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
<img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
<img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
<img src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io">
<img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS">
</p>

Chatters is a sleek and intuitive real-time chat application that allows you to connect with friends, family, and colleagues instantly. With a modern and user-friendly interface, staying in touch has never been easier.

<p align="center">
<img src="https://placehold.co/800x400/334155/E2E8F0?text=Chatters+App+Screenshot" alt="Chatters Application Screenshot"/>
</p>

✨ Features
⚡ Real-Time Messaging: Instantly send and receive messages with our low-latency WebSocket integration using Socket.io.

🔐 User Authentication: Secure user registration and login with JWT (JSON Web Tokens) to protect your conversations.

🟢 Online Status: See who's online and ready to chat in real-time.

🔍 User Search: Easily find and connect with other users on the platform.

🎨 Sleek UI: A modern and visually appealing design built with Tailwind CSS and DaisyUI for a seamless user experience.

📱 Responsive Design: Chat on the go with a fully responsive interface that works on any device.

🔔 Notifications: Get notified of new messages with a subtle sound alert.

💻 Tech Stack
Category

Technology

Frontend

React React Router Tailwind CSS DaisyUI Zustand Axios Socket.io-client

Backend

Node.js Express.js Socket.io JWT bcryptjs

Database

MongoDB Mongoose

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Make sure you have the following installed on your machine:

Node.js (v14 or higher)

npm

MongoDB

Installation & Setup
Clone the repository:

git clone https://github.com/your-username/chat-application.git
cd chat-application

Install Backend Dependencies:
Navigate to the root directory and run:

npm install

Install Frontend Dependencies:

npm install --prefix frontend

Set Up Environment Variables:
Create a .env file in the root directory and add the following variables. Replace the placeholder values with your actual credentials.

PORT=3000
MONGODB_CONNECT=<your_mongodb_connection_string>
JWT_SECRET=<your_super_secret_jwt_key>
SECURE=development

Run the Application:
You can run both the frontend and backend concurrently from the root directory with a single command:

npm run build
npm start

Or, run them separately for development:

Start the backend server (from the root directory):

npm run dev

Start the frontend client (from the frontend directory):

npm run dev

The application should now be running! Open your browser and navigate to http://localhost:5173.

📂 Project Structure
chat-application/
├── backend/
│   ├── DB/
│   ├── Middleware/
│   ├── Models/
│   ├── rout/
│   ├── routControlers/
│   ├── Socket/
│   ├── utils/
│   └── index.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── context/
│   │   ├── home/
│   │   ├── login/
│   │   ├── register/
│   │   ├── utils/
│   │   ├── Zustans/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── vite.config.js
└── package.json

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

📫 Contact
Shashwata Saha - shashwata.saha32@gmail.com

Project Link: https://github.com/shashwata32/chat-application