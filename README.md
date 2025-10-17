
**MediCare — Doctor Appointment Booking System**

A modern web application built with the **MERN** stack (MongoDB, Express, React, Node.js) that allows users to register, log in, book appointments with doctors, and manage their profiles.

## 💡 Features

- User registration & login (doctor/patient authentication)  
- JWT-based secure authentication  
- View list of doctors and their availability  
- Book, reschedule, or cancel appointments  
- User dashboard to manage appointments & profile  
- Admin panel (planned for future enhancement)  
- Email confirmation (optional / future scope)  

## 🛠️ Tech Stack

- **Frontend**: React.js, React Router, Axios, Tailwind CSS / CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JSON Web Tokens (JWT)  

## 📂 Project Structure

```

Doctor_Appointment/
├── client/       # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.js
│       └── index.js
├── server/       # Node / Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
├── .gitignore
├── package.json
└── README.md

````

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB (local or hosted)
- (Optional) An SMTP / email service for email confirmations

### Installation & Running Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/khushikumari0202/MediCare.git
   cd MediCare
````

2. **Setup the backend**

   ```bash
   cd server
   npm install
   npm run dev   # or npm start
   ```

   * Make sure to configure your environment variables (e.g. MongoDB URI, JWT secret, email credentials) in a `.env` file in the `server` directory.

3. **Setup the frontend**

   ```bash
   cd ../client
   npm install
   npm run dev
   ```

4. Open your browser:

   * Frontend: `http://localhost:3000`
   * Backend API: `http://localhost:5000`

## ⚙️ Configuration & Environment Variables

In the **server** directory, create a `.env` file with variables like:

```text
PORT=5000
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_HOST=smtp.example.com
EMAIL_PORT=587
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```

Adjust according to your email provider or mailing service.

## 🧪 Usage & Testing

* Register as a **patient** or **doctor**
* Log in to your account
* Browse doctors’ availability
* Book, cancel or manage appointments
* View your appointments on dashboard

(*Future scope: email confirmation for registration, admin panel, notification system, payment integration, etc.*)

## 📬 Deployment

You can deploy the backend (Express + MongoDB) using services like Heroku, Vercel, or DigitalOcean, and deploy the frontend (React) to services like Vercel, Netlify, or GitHub Pages.
Make sure to correctly set up environment variables and CORS settings.

## 🙋‍♀️ Author & Acknowledgements

* **Khushi Kumari**

  * LinkedIn: [Khushi Kumari](https://www.linkedin.com/in/khushi-kumari-582a02241/)
  * GitHub: [@khushikumari0202](https://github.com/khushikumari0202)

If you like this project, please **⭐ Star** this repository, contribute via pull requests, or share it!

## 📝 License

This project is open source — feel free to copy, modify, or use it in your own projects.

```

```

