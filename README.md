## Hostel Complaint Management System

## Project Overview

**Hostel Complaint Management System** is a full-stack web application designed to streamline the management of complaints raised by students residing in hostels. The system allows users to submit complaints, track their statuses, and provides role-based dashboards for different users (e.g., students, resident tutors, hostel wardens, campus coordinators).

The project is built using the **MERN stack** (MongoDB, Express.js, React, Node.js) with an intuitive interface to manage complaints, including mess, maintenance, plumbing, electrical issues, and more.



## 🚀 Live Demo

Check out the live demo of the Hostel Complaint Management System:

🔗 [Live Demo](https://hostel-complaint-management-frontend.vercel.app/)


## 📂 Project Structure

Hostel-Complaint-Management-System/

├── Hostel-Complaint-Management-Frontend/   # Frontend code (React)
├── Hostel-Complaint-Management-Backend/    # Backend code (Node.js/Express.js)
├── .gitignore                             # Git ignore file
├── README.md                              # Project description



## 🔧 Technologies Used

- **Frontend:**
  - React.js
  - React Router for routing
  - Axios for HTTP requests
  - Vercel for deployment

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB with Mongoose for database management
  - Render for deployment

- **Other:**
  - Git for version control
  - JWT for authentication
  - NodeMailer for OTP email functionality

---

## 🖥️ Features

- **Role-based access**: Different dashboards for students, resident tutors (RT), hostel wardens, and campus coordinators (CC).
- **Complaint Management**: Students can submit complaints, and RTs/CCs can track the status.
- **Graphical Complaint Tracking**: Visual representation of complaint statuses (Pending, Accepted, Rejected).
- **OTP-based Password Reset**: Users can reset their password via OTP sent to their registered email.
- **Admin functionalities**: Hostel wardens and campus coordinators can manage users and complaints.

---

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Nomimian01/Hostel_Complaint_Management_System.git
````

### 2. Set up the Backend

* Navigate to the backend directory:

```bash
cd Hostel-Complaint-Management-System/Hostel-Complaint-Management-Backend
```

* Install dependencies:

```bash
npm install
```

* Create a `.env` file with your MongoDB URI and JWT secret (check `.env.example` for guidance).

* Start the backend server:

```bash
npm start
```

### 3. Set up the Frontend

* Navigate to the frontend directory:

```bash
cd Hostel-Complaint-Management-System/Hostel-Complaint-Management-Frontend
```

* Install dependencies:

```bash
npm install
```

* Start the frontend server:

```bash
npm start
```

Now, open your browser and visit [http://localhost:3000](http://localhost:3000) to see the app in action.


## 📑 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## 📝 Key Points:
- **Live Demo Link**: You can now access the **Live Demo** directly on Vercel.
- **Frontend and Backend Repos**: These are clearly linked to the respective GitHub repositories.
- **Technologies & Features**: I've included the tech stack and project features for clarity.
- **Setup Instructions**: Instructions for running the project locally.

