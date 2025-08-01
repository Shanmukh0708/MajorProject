
# 🎓 Smart Skill Mentor

An AI-powered web platform that bridges the gap between theoretical learning and industry-required skills. The system personalizes student growth paths by analyzing academic performance, personality traits, and interests, then recommends relevant career tracks and real-world problem-solving challenges.

---

## 🚀 Key Features

- **AI-Powered Skill Mapping**: Uses student data to generate personalized learning paths.
- **Career Track Recommendations**: Aligns interests and academic records with potential career domains.
- **Industry Problem Bank**: Real-world challenges from industry mentors to develop practical skills.
- **Progress Dashboard**: Visual feedback on skill acquisition, goals, and active learning.
- **Admin & Mentor Panels**: Separate roles to manage content and evaluate student involvement.

---

## 🧠 How It Works

1. **User Registration**: Students create a profile with academic history and interests.
2. **Data Analysis**: AI engine evaluates inputs and matches users with suitable domains (e.g., AI/ML, Web Dev, Cybersecurity).
3. **Recommendation Engine**: Generates personalized challenges, resources, and mentors.
4. **Progress Monitoring**: Tracks activities, achievements, and suggestions over time.

---

## 🛠️ Tech Stack

| Layer         | Technologies Used                            |
|--------------|-----------------------------------------------|
| Frontend     | React, HTML5, CSS3, Tailwind CSS              |
| Backend      | Node.js, Express.js                           |
| Database     | MongoDB                                       |
| AI Module    | Python (scikit-learn, pandas) via microservice |
| Others       | JWT Auth, REST APIs, Chart.js, GitHub Actions |

---

## 📂 Project Structure

```
smart-skill-mentor/
├── client/                    # React frontend
│   ├── components/
│   ├── pages/
│   └── App.js
├── server/                    # Node.js backend
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── app.js
├── ai-module/                 # Python microservice (optional)
│   └── ai_engine.py
├── .env
├── package.json
└── README.md
```

---

## 📸 Screenshots

> *(Add images of the dashboard, AI recommendation page, admin panel, etc.)*

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smart-skill-mentor.git
   cd smart-skill-mentor
   ```

2. **Install backend dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../client
   npm install
   ```

4. **(Optional) Set up Python AI module**
   ```bash
   cd ../ai-module
   pip install -r requirements.txt
   ```

5. **Start backend and frontend**
   ```bash
   cd ../server && npm run dev
   # In a new terminal
   cd ../client && npm start
   ```

---

## ✨ Use Cases

- Personalized learning recommendation system for universities.
- Mentor-student pairing based on skill needs.
- EdTech platforms targeting job readiness.

---

## 📜 License

This project is under the MIT License — free for use with attribution.

---

## 🤝 Contributing

Want to contribute? Pull requests are welcome! Please open an issue to suggest improvements or report bugs.

---

## 💡 Future Enhancements

- NLP-powered feedback summaries
- Mentor chat integration
- Certification & badges for skill milestones

---

## 🙏 Acknowledgements

- AICTE & EdTech initiatives
- Open source contributors and mentors
- React, Node, MongoDB, Python ML community
