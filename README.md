# FS_Dev-Audicha
Student Commute Optimizer  🚗– A full-stack carpooling and route-sharing app for students.


## 📌 Problem Statement
The **Student Commute Optimizer** is a carpooling and route-sharing application designed for students.  
Instead of commuting individually, students can **share rides** efficiently by matching routes.

**How it works:**

**Frontend (Student Interface):**
- Students enter their **home location** and **destination** (school/college).  
- Displays **nearby students** traveling in the same direction.  
- Students can click on another student to **start a chat** (anonymous).  

**Backend (System Operations):**
- Compares multiple student routes.  
- Identifies **overlaps or proximity** in travel paths.  
- Suggests **possible carpooling matches**.  
- Each student has a **unique anonymous username** (cannot be duplicated).
- <img width="741" height="501" alt="image" src="https://github.com/user-attachments/assets/5ffdc00d-f4fb-46c7-9cc9-4f8fb52d1438" />


  https://github.com/devaudicha/FS_Dev-Audicha/blob/3c5d4cc39264ad07b6097eeeac22c98c13afb526/431eaa8e-57a0-48ab-a52d-426f6adfa622.png

---

## ⚡ Features
- Anonymous login with **auto-generated unique usernames**  
- Enter home and destination for commute  
- View **nearby students** on similar routes  
- Click to chat with nearby students (basic UI implemented in MVP)  
- Lightweight and simple **MVP ready for 90-minute submission**  

---

## 🛠 Tech Stack
- **Frontend:** Next.js, TailwindCSS, React  
- **Backend:** Node.js, Express.js  
- **Real-time chat:** Optional Socket.IO (can be mocked)  
- **Database:** In-memory for MVP / MongoDB for full version  
- **Hosting (optional):** Vercel (frontend), Render/Heroku (backend)  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/devaudicha/FS_Dev-Audicha.git
cd FS_Dev-Audicha

---

### 2. Setup Backend

cd backend
npm install
npm run dev


Runs backend server on http://localhost:5000

---

3. Setup Frontend
cd ../frontend
npm install
npm run dev

