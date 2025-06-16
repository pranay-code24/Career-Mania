# Career Mania – A Job Portal 💼

Career Mania is a full-stack job portal designed to streamline the job search and hiring process for both candidates and recruiters. Built using the MERN stack, the platform offers secure authentication, resume management, and intelligent job matching features.

---

## 🔧 Features

- Candidate and recruiter role-based authentication using JWT  
- AI-powered keyword-based job-candidate relevance logic  
- Resume upload and management using Multer and Cloudinary  
- Job creation, listing, filtering, and application workflows  
- Responsive and clean user interface  
- Secure data handling with encrypted passwords via bcrypt  

---

## 🧠 Tech Stack

**Frontend:**
- React.js, JavaScript  
- Tailwind CSS  

**Backend:**
- Node.js, Express.js  
- MongoDB, Mongoose  
- JWT for authentication  
- Bcrypt for password hashing  
- Multer & Cloudinary for file uploads  

---

## 🚀 Project Structure

```

/frontend
└── React client (UI, job listings, auth)

/backend
└── Express server (routes, controllers, DB models)

/config
└── JWT setup, Cloudinary config, MongoDB connection

```

---

### ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/pranay-code24/Career-Mania.git
cd Career-Mania
```

### 2. Install dependencies

```bash
cd backend
npm install

cd ../frontend
npm install
```

### 3. Configure environment variables

Create a `.env` file in `/backend` with:

```env
MONGO_URI=<your_mongo_uri>
JWT_SECRET=<your_jwt_secret>
CLOUDINARY_CLOUD_NAME=<cloud_name>
CLOUDINARY_API_KEY=<api_key>
CLOUDINARY_API_SECRET=<api_secret>
```

---

### 4. Run the application

```bash
# Backend
cd backend
npm run dev

# Frontend
cd ../frontend
npm start
```

---

## 📦 Usage

* Recruiters can create and manage job listings
* Candidates can browse and apply to jobs
* Resumes are uploaded and stored via Cloudinary
* Authenticated sessions with secure JWT tokens

---

## ✅ Testing

Includes manual testing for:

* Job creation and filtering
* Resume upload and access control
* Authentication and protected routes

---

## 🧑‍💻 Author

**Pranay Gumashta**
[GitHub Profile](https://github.com/pranay-code24)
Built with ❤️ using the MERN Stack