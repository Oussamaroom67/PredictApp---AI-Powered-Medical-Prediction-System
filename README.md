# 🌍 **PredictApp - AI-Powered Medical Prediction System**  

PredictApp is an intelligent system that predicts diseases based on symptoms. It consists of three main components:  

- **Frontend (React.js)** – User-friendly interface for entering symptoms and viewing results.  
- **Backend (Node.js & Express.js)** – Manages user authentication and request handling.  
- **Machine Learning API (Flask, Python)** – Predicts diseases using a trained model.  

---

## 🔗 **Project Repositories**  

| Component        | Repository Link |
|-----------------|----------------|
| **Frontend**  | [Frontend Repo](https://github.com/Oussamaroom67/PredictApp) |
| **Backend**   | [Backend Repo](https://github.com/Oussamaroom67/ApiPredictApp) |
| **ML Model API** | [ML API Repo](https://github.com/Oussamaroom67/modelApiPredictApp) |

---

## 🏗 **Project Overview**  

![Architecture Diagram](https://raw.githubusercontent.com/Oussamaroom67/docs-predictapp/main/architecture.jpg)  

1️⃣ The **frontend** allows users to input symptoms.  
2️⃣ The **backend** processes requests and communicates with the **ML API**.  
3️⃣ The **ML API** predicts the disease and returns results, including confidence scores and recommendations.  

---

## 🚀 **How to Run the Project**  

### 1️⃣ Clone All Repositories  
```sh
git clone https://github.com/Oussamaroom67/PredictApp.git
git clone https://github.com/Oussamaroom67/ApiPredictApp.git
git clone https://github.com/Oussamaroom67/modelApiPredictApp.git
```

### 2️⃣ Install Dependencies  
```sh
cd PredictApp && npm install  
cd ApiPredictApp && npm install  
cd modelApiPredictApp && pip install -r requirements.txt  
```

### 3️⃣ Run Each Service  
```sh
npm start  # Frontend (http://localhost:3000)  
npm start  # Backend (http://localhost:5000)  
python api.py  # ML API (http://localhost:8080)  
```

---

## 🔥 **API Overview**  

### **Predict Disease** (`POST /predict`)  
**Request:**  
```json
{ "symptoms": ["fatigue", "fever", "cough"] }
```
**Response:**  
```json
{
  "disease": "Influenza",
  "confidence": 0.87,
  "description": "Influenza is a viral infection affecting the respiratory system...",
  "precautions": ["Drink plenty of water", "Get rest", "Consult a doctor"]
}
```

---

## 🤝 **Contributors**  
Developed by **Oussama Nouhar, Omaima Siaf, and Souhayla Ghanem**.  

---

## 📜 **License**  
This project is licensed under the **MIT License**.  

