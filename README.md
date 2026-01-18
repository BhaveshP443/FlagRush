

````md
# 🚩 FlagRush
### A Social Media Community for Hackers

FlagRush is a social media community platform designed specifically for hackers and cybersecurity enthusiasts. It allows users from around the world to practice skills, participate in challenges, collaborate, and grow together.

---

## 🚀 Features

- 🔍 Explore curated links and identify vulnerabilities to sharpen hacking skills  
- 🏆 Participate in contests and challenges  
- 🤝 Connect with other hackers and build a network  
- 💬 Real-time chat to exchange ideas and knowledge  
- 🧠 Discussion forums for cybersecurity-related topics  

---

## 🛠 Tech Stack

- **Frontend:** React + Vite  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Authentication:** JWT  

---

## 📦 Installation

Make sure **Node.js** and **npm** are installed on your system.

---

## 📁 Clone the Repositories

### Frontend
```bash
git clone https://github.com/<YOUR_USERNAME>/FlagRush.git
cd FlagRush-client
````

### Backend

```bash
git clone https://github.com/<YOUR_USERNAME>/FlagRush-server.git
cd FlagRush-server
```

---

## 📥 Install Dependencies

Run this command in **both frontend and backend directories**:

```bash
npm install
```

---

## ⚙️ Environment Setup (Backend)

Create a `.env` file in the backend root directory:

```env
PORT=5000

DATABASE_HOST=mongodb+srv://<username>:<PASSWORD>@cluster0.mongodb.net/flagrush
DATABASE_PASSWORD=your_mongodb_user_password

SECRET_KEY=your_jwt_secret_key
EXPIRES=90d
EXPIRES_IN=90
```

⚠️ **Important:** Add `.env` to `.gitignore` and never commit it to GitHub.

---

## ▶️ Running the Project

### Start Backend Server

```bash
npm start
```

Backend will run on:

```
http://localhost:5000
```

---

### Start Frontend Server

```bash
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

## 🧪 Usage

* Register and log in to the platform
* Participate in challenges and contests
* Chat and collaborate with other users
* Share and discuss cybersecurity knowledge

---

## 🤝 Contributing

We welcome community contributions!

### Steps to contribute:

1. Fork the repository
2. Clone your fork

   ```bash
   git clone https://github.com/<YOUR_USERNAME>/FlagRush.git
   ```
3. Create a new branch

   ```bash
   git checkout -b feature-name
   ```
4. Commit your changes
5. Push and create a Pull Request

All contributions are reviewed before merging.

---



