# 🏠 Real Estate Price Visualizer & Predictor

An interactive **web application** that helps users **analyze, visualize, and predict real estate prices** across cities and suburbs in India.  
Built with a **React frontend** for rich visualizations and a **Flask backend** that serves a trained **CatBoost machine learning model** for price prediction.  

---

## ✨ Features

- 📊 **Visualizations Dashboard**  
  - Explore price distribution, property types, city trends, and correlation insights.  
  - Compare different parameters with interactive charts.  

- 📑 **Dataset Explorer**  
  - Search, sort, and paginate through the dataset.  
  - CSV download support for further analysis.  

- 🤖 **Price Prediction**  
  - Enter city, suburb, property type, builder, and other parameters.  
  - Get instant ML-based predicted price.  

- 🎨 **Modern UI/UX**  
  - Responsive React app with cool visuals, charts (Recharts), and smooth navigation.  

---

## 🛠️ Tech Stack

**Frontend (React)**  
- React
- React Router
- Recharts (for charts)  
- Custom CSS  

**Backend (Flask API)**  
- Python  
- Flask / FastAPI  
- CatBoost ML model  

**Other Tools**  
- Pandas, NumPy (data preprocessing)  
- GitHub + Vercel + Render (deployment)  

---

---

## 🚀 Setup Instructions

### 1️⃣ Clone the repo
```bash
git clone https://github.com/Krish2673/Real_Estate_Visualizer.git
cd Real_Estate_Visualizer
```

2️⃣ Backend Setup
```bash
pip install -r requirements.txt
python app.py
```

3️⃣ Frontend Setup
```bash
npm install
npm run dev
```

---

## 🌍 Live Demo

- 🔗 **Frontend (React App):** [View Live](https://real-estate-visualizer.vercel.app/)
- 🔗 **Backend (Flask API):** [API Endpoint](https://real-estate-visualizer-backend.onrender.com)

*(Frontend and backend are connected – prediction requests from the React app are served by the Flask API.)*

---
