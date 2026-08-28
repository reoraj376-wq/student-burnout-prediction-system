# 🧠 Student Burnout & Stress Level Prediction System

A comprehensive mobile application that predicts student burnout and stress levels using machine learning. The system analyzes behavioral, academic, and psychosocial factors to provide early intervention recommendations.

## 📱 Features

### 1. **Single Prediction Module**
- Input student behavioral & academic profile
- Real-time burnout score prediction
- Risk status classification (Low, Moderate, High)
- Visual burnout gauge index

### 2. **Batch Prediction Module**
- Upload multiple student records
- Process predictions in bulk
- Generate performance reports
- Export results to CSV/PDF

### 3. **Model Analytics Dashboard**
- Model performance metrics
- Algorithm comparison (Accuracy, R² Score, MAE)
- Real-time inference engine
- Pre-trained ML model integration

## 📊 Input Parameters

### Demographics & Academics
- Age
- Gender
- Course/Degree
- Academic Year
- CGPA (0.00 - 10.00)
- Attendance Percentage (%)

### Daily Routine & Lifestyle
- Daily Study Hours
- Daily Sleep Hours
- Screen Time Hours
- Physical Activity (Hours/Day)
- Sleep Quality (1-10)
- Internet Quality

### Psychosocial Stressors & Health
- Anxiety Score (1-10)
- Depression Score (1-10)
- Academic Pressure (1-10)
- Financial Stress (1-10)
- Social Support System (1-10)

## 🛠️ Tech Stack

### Frontend (Mobile)
- **Framework:** React Native / Flutter
- **State Management:** Redux / GetX
- **UI Components:** Native Base / Flutter Material
- **Charts:** React Native Chart Kit / FL Chart
- **HTTP Client:** Axios / Dio

### Backend
- **Runtime:** Node.js / Python
- **Framework:** Express.js / Flask
- **Database:** MongoDB / PostgreSQL
- **API:** RESTful API
- **Authentication:** JWT

### Machine Learning
- **Model Type:** Random Forest Regression
- **Framework:** Scikit-learn
- **Accuracy:** 93.39%
- **R² Score:** 0.9259
- **MAE:** 3.1407

### DevOps & Deployment
- **Version Control:** Git/GitHub
- **CI/CD:** GitHub Actions
- **Deployment:** Heroku / AWS
- **Container:** Docker (Optional)

## 📋 System Requirements

### Mobile App Requirements
- **Minimum OS:** Android 8.0+ / iOS 12.0+
- **RAM:** 2GB minimum
- **Storage:** 100MB
- **Internet:** WiFi/4G connection required

### Backend Requirements
- **Node.js:** v14.0+ or Python 3.8+
- **Database:** MongoDB 4.4+ or PostgreSQL 12+
- **Memory:** 1GB RAM minimum
- **CPU:** Dual-core processor

## 🚀 Getting Started

### Prerequisites
```bash
# Backend
- Node.js v14+ / Python 3.8+
- npm / pip
- Git

# Mobile
- React Native CLI / Flutter SDK
- Android Studio / Xcode
- Emulator or Physical Device
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/reoraj376-wq/student-burnout-prediction-system.git
cd student-burnout-prediction-system
```

2. **Backend Setup**
```bash
cd backend
npm install  # or pip install -r requirements.txt
cp .env.example .env
npm start
```

3. **Mobile App Setup**
```bash
cd mobile
npm install  # or flutter pub get
npx react-native run-android  # or flutter run
```

## 🗂️ Project Structure

```
student-burnout-prediction-system/
├── frontend/                 # React Native mobile app
│   ├── src/
│   │   ├── screens/
│   │   ├── components/
│   │   ├── navigation/
│   │   ├── redux/
│   │   └── utils/
│   ├── App.js
│   └── package.json
├── backend/                  # Node.js/Flask API server
│   ��── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
├── ml-model/                 # ML model files
│   ├── model.pkl
│   ├── train.py
│   └── predict.py
├── docs/                     # Documentation
├── .gitignore
├── docker-compose.yml
└── README.md
```

## 📈 Model Performance

| Metric | Value |
|--------|-------|
| Algorithm | Random Forest Regression |
| Accuracy Rate | 93.39% |
| R² Score | 0.9259 |
| Mean Absolute Error (MAE) | 3.1407 |

## 🔄 API Endpoints

### Prediction
- `POST /api/predict` - Single prediction
- `POST /api/batch-predict` - Batch predictions

### Analytics
- `GET /api/model-metrics` - Model performance metrics
- `GET /api/predictions/history` - Prediction history

### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login

## 🛡️ Security

- JWT-based authentication
- Input validation on all endpoints
- Rate limiting (100 requests/hour)
- HTTPS encryption
- SQL injection protection
- CORS configuration

## 📱 Mobile Screenshots

1. **Single Prediction Module** - Input form with sliders and dropdowns
2. **Model Analytics** - Performance metrics and algorithm comparison
3. **Burnout Score Result** - Visual gauge with risk status

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**reoraj376-wq**

## 📞 Support

For support, email support@burnoutsystem.com or open an issue on GitHub.

## 🎯 Roadmap

- [ ] Real-time notification system
- [ ] Counselor dashboard
- [ ] Intervention recommendations engine
- [ ] Historical trend analysis
- [ ] Mobile app deployment
- [ ] API rate limiting enhancement
- [ ] Advanced analytics dashboard

---

**Last Updated:** August 28, 2026
**Version:** 1.0.0
