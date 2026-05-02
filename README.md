# 🏙️ CityAssist

A smart city issue reporting and management platform that empowers citizens to report road and civic problems while enabling administrators to manage, track, and resolve complaints efficiently — powered by AI-based road condition detection.

---

## 🚀 Live Demo
> Coming Soon

---

## 📸 Screenshots

> _Add your app screenshots here_

---

## ✨ Features

### 👤 Citizen Side
- 📝 Register and log in securely
- 📸 Upload images of road/civic issues
- 📍 Submit complaints with location details
- 🔔 Track complaint status in real time

### 🛠️ Admin Side
- 📊 Admin dashboard with complaint overview
- ✅ Accept / ❌ Reject complaints
- 🔍 View detailed issue reports
- 📢 Post city updates and announcements

### 🤖 AI / Machine Learning
- 🧠 CNN model to classify road conditions (Clean vs Dirty)
- 🖼️ Automatic image analysis on complaint submission
- 📁 Trained on custom dataset (`cleandirty-road-classification`)

### 📹 Communication
- 🎥 JitsiMeeting integration for video communication between admin and citizens

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Machine Learning | Python, TensorFlow/Keras, CNN |
| Video | Jitsi Meet API |
| Auth | JWT Authentication |
| File Upload | Image Upload Component |

---

## 📁 Project Structure

```
CityAssist/
├── Frontend/               # React.js frontend
│   ├── src/
│   │   ├── components/     # UI Components
│   │   │   ├── Navbar.js
│   │   │   ├── AdminDashboard.js
│   │   │   ├── AdminNavBar.js
│   │   │   ├── AdminIssueDetails.js
│   │   │   ├── JitsiMeeting.js
│   │   │   ├── ImageUpload.js
│   │   │   ├── Cityupdate.js
│   │   │   ├── Connect.js
│   │   │   └── Completed.js
│   │   └── App.js
│   └── public/
├── Backend/                # Node.js + Express backend
│   └── ...
├── manchine/               # ML model
│   ├── model.py
│   ├── predict.py
│   └── road_classifier_cnn.h5
└── datasets/
    └── clean_dirty_road/   # Training dataset
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js >= 14
- Python >= 3.8
- MongoDB

### 1. Clone the Repository
```bash
git clone https://github.com/Logical-DV/CityAssist.git
cd CityAssist
```

### 2. Setup Backend
```bash
cd CityAssist_-main/Backend
npm install
npm start
```

### 3. Setup Frontend
```bash
cd CityAssist_-main/Frontend
npm install
npm start
```

### 4. Setup Machine Learning
```bash
cd CityAssist_-main/manchine
pip install -r requirements.txt
python predict.py
```

### 5. Environment Variables
Create a `.env` file in the Backend folder:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss what you would like to change.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Logical-DV**
- GitHub: [@Logical-DV](https://github.com/Logical-DV)

---

⭐ If you found this project helpful, please give it a star!
