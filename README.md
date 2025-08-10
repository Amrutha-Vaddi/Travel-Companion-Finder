# Travel-Companion-Finder

# 🌍 Travel Companion Finder System

A full-stack web application that helps travelers find compatible companions based on **location**, **travel dates**, and **shared interests**. The platform includes **secure authentication**, **trip & profile management**, and **real-time chat** for seamless travel networking.

---

## 🚀 Features

- **User Authentication** – Secure login & registration using JWT and bcrypt encryption.
- **Profile Management** – Edit personal details, update travel interests, and upload/change/delete profile photos.
- **Trip Management** – Create, update, delete trips with location & date details.
- **Matching Algorithm** – Suggests companions based on location, date overlap, and shared interests.
- **Real-Time Chat** – WebSocket (STOMP + SockJS) powered messaging with persistent storage in MySQL.
- **Responsive UI** – Designed with React Bootstrap for smooth user experience on all devices.

---

## 🛠 Tech Stack

**Frontend:**
- React.js
- React Bootstrap
- Axios

**Backend:**
- Spring Boot
- MySQL
- JWT Authentication
- WebSocket (STOMP + SockJS)

**Others:**
- REST API
- bcrypt password encryption

---




---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/travel-companion-finder.git


2️⃣ Backend Setup (Spring Boot)
cd backend
# Update application.properties with your MySQL credentials
mvn spring-boot:run


3️⃣ Frontend Setup (React)
cd frontend
npm install
npm start



📌 Future Enhancements
AI-based matching recommendations.

Group trip creation & planning.

In-app notifications for new matches & messages.
## 📂 Project Structure

