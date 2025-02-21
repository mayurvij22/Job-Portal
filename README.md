

🏢 Job Portal (MERN Stack)

A Job Portal web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows employers to post jobs and job seekers to apply for job listings.

🚀 Features

	•	User Authentication (JWT-based for job seekers & recruiters)
	•	Job Posting & Management (Create, Edit, Delete jobs)
	•	Job Search & Filtering (Based on title, location, category, etc.)
	•	Application Tracking (Employers can manage applicants)
	•	Profile Management (Users can update resumes & details)
	•	Admin Dashboard (For managing users & jobs)

🛠 Tech Stack

	•	Frontend: React.js, Redux (for state management), Tailwind CSS
	•	Backend: Node.js, Express.js, MongoDB
	•	Authentication: JSON Web Token (JWT), bcrypt
	•	Database: MongoDB with Mongoose ORM
	•	Deployment: Vercel (Frontend), Render/Heroku (Backend)

📂 Project Structure

JobPortal/
│── client/        # React frontend  
│── server/        # Node.js backend  
│── models/        # Mongoose models  
│── routes/        # Express routes  
│── controllers/   # Business logic  
│── config/        # Config files (DB, JWT, etc.)  
│── middleware/    # Authentication & validation middleware  
│── public/        # Static assets  
│── .env           # Environment variables  
│── README.md      # Project documentation  

📦 Installation

1️⃣ Clone the repository:

git clone https://github.com/your-username/job-portal.git
cd job-portal

2️⃣ Install dependencies for both frontend & backend:

cd client
npm install
cd ../server
npm install

3️⃣ Set up environment variables:
Create a .env file in the server/ folder and add:

MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  
PORT=5000  

4️⃣ Start the development servers:

# Backend
cd server
npm run dev

# Frontend
cd client
npm start

🚀 API Endpoints

Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login user
GET	/api/jobs	Get all jobs
POST	/api/jobs	Create a new job
GET	/api/jobs/:id	Get job details
PUT	/api/jobs/:id	Update job
DELETE	/api/jobs/:id	Delete job

🤝 Contributing

	1.	Fork the repo
	2.	Create a new branch (git checkout -b feature-branch)
	3.	Commit your changes (git commit -m "Add new feature")
	4.	Push to your branch (git push origin feature-branch)
	5.	Open a Pull Request

📜 License

This project is licensed under the MIT License.
