MediCare — Doctor Appointment Booking System

A modern web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) to allow users (patients) to register, log in, browse doctors, book appointments, and manage their profiles. Admin or doctor panels may be added in future.

🩺 Features

User & Doctor Authentication — Register & login with role-based access

Book & Manage Appointments — Patients can book, view, cancel appointments

Doctor Availability — Doctors can define time slots (future implementation)

User Dashboard — View upcoming & past appointments

JWT Authentication — Secure token-based sessions

API Integration via Axios

Routing — React Router for client-side navigation

Styling — Tailwind CSS (or plain CSS)

Modular folder structure for separation of concerns

🛠️ Tech Stack & Tools
Layer	Technology
Database	MongoDB
Backend	Node.js, Express.js
Frontend	React.js
Authentication	JSON Web Tokens (JWT)
API	Axios
Routing	React Router
Styling	Tailwind CSS / CSS
📂 Folder Structure
Doctor_Appointment/
├── client/             # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.js
│       └── index.js
├── server/             # Node / Express Backend
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .gitignore
├── package.json
└── README.md

🚀 Getting Started

Follow these steps to run the project locally.

1. Clone the repository
git clone https://github.com/khushikumari0202/MediCare.git
cd MediCare

2. Setup the Backend
cd server
npm install
npm run server


By default, the server may start at http://localhost:5000 (or another port you configure).

3. Setup the Frontend (Client)

In a new terminal:

cd client
npm install
npm run dev


The React app should start at http://localhost:3000 (or the port you configure).

4. Access the Application

Frontend: http://localhost:3000

Backend (API): http://localhost:5000

🔧 Environment Setup & Configuration

You’ll likely need to create a .env file in the server folder with configurations such as:

PORT=5000
MONGODB_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_secret_key>


Ensure your MongoDB instance is running and accessible.

✅ Future Enhancements / Scope

Email confirmation / verification

Admin dashboard (manage doctors, users, appointments)

Improve UI/UX / add themes

Security improvements (rate limiting, input validation)

Notifications / reminders (email, SMS)

Doctor panel to manage availability & appointments

Patient reviews & ratings

👤 Author

Khushi Kumari
LinkedIn

If you like this project, please ⭐ the repository and feel free to contribute or give feedback!
