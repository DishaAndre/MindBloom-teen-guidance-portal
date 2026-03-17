# MindBloom – Teen Guidance Portal

MindBloom is a safe, friendly, and interactive web platform designed for children aged 10–13 to ask questions about emotional, social, and personal concerns and receive guidance from trusted counselors.

The platform focuses on creating a **non-judgmental, supportive, and educational environment** for young users.

---

## 🚀 Key Features

### 👦 Child User

* Register and login securely
* Ask questions 
* Select categories (school, bullying, friendship, etc.)
* Mark questions as **urgent / private**
* Track question status:

  * Submitted
  * Under Review
  * Assigned to Counselor
  * Answered
* View counselor replies
* Access **Knowledge Center**
* Attempt **Mini Quizzes**
* Earn badges (UI-based feature)

---

### 🧑‍⚕️ Counselor

* Dashboard to view assigned questions
* Filter questions:

  * Urgent
  * New
  * Answered
* Respond using child-friendly language
* Use safe response templates
* Flag risky or sensitive cases
* Create educational articles

---

### 🛠️ Admin

* Manage all users (children & counselors)
* View and moderate questions
* Assign questions to counselors
* Appropriate content filtering
* Approve/reject articles
* Remove unsafe content

---

## 🎨 UI/UX Highlights

* Kid-friendly interface
* Soft color palette 
* Rounded cards and clean layout
* Large readable fonts
* Friendly icons and simple navigation
* Emotionally safe and welcoming design

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* Tailwind CSS
* React Hooks
* Heroicons 

### Backend

* Node.js
* Express.js

### Database

* JSON file (local storage for prototype)

---

## 📁 Project Structure

mindbloom-teen-guidance-portal/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── data.json
│   └── package.json
│
├── README.md
└── .gitignore


---

## How to Run the Project Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/mindbloom-teen-guidance-portal.git
cd mindbloom-teen-guidance-portal
```

---

### 2️⃣ Run Backend

```bash
cd backend
npm install
node server.js
```

Server will run on:
http://localhost:5000

---

### 3️⃣ Run Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:
http://localhost:5173

---

## Sample Data Included

* Example user accounts
* Sample questions
* Counselor replies
* Educational articles
* Quiz questions

---

## Project Objective

To build a **safe digital space** where pre-teens can:

* Express their concerns freely
* Get trusted guidance
* Learn healthy habits
* Avoid unsafe online information

---

This project is developed as part of a **UI/UX academic course** and demonstrates full-stack development with a focus on usability, safety, and accessibility for young users.

---
