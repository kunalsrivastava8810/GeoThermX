# 🌍 GeoThermX

### AI-Powered Urban Heat Island Intelligence & Mitigation Platform

**Developed by:** Kunal Srivastava • Shivam Gupta • Kumar Ankit

**Bharatiya Antariksh Hackathon 2026 (BAH 2026)**

> Transforming satellite-derived environmental data into actionable climate intelligence through Artificial Intelligence, Machine Learning, and Geospatial Analytics.

![Python](https://img.shields.io/badge/Python-3.11+-blue)
![React](https://img.shields.io/badge/React-19-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![AI](https://img.shields.io/badge/AI-Gemini-orange)
![ISRO](https://img.shields.io/badge/ISRO-BAH%202026-success)

---

## 🚀 Overview

GeoThermX is an AI-powered geospatial intelligence platform developed for the **Bharatiya Antariksh Hackathon 2026 (BAH 2026)**. The platform combines satellite-derived environmental indicators, machine learning models, and autonomous AI agents to identify, analyze, and mitigate **Urban Heat Island (UHI)** effects.

By leveraging predictive analytics and digital twin technology, GeoThermX enables policymakers, urban planners, and environmental agencies to make data-driven decisions for sustainable urban development and climate resilience.

---

## 🎯 Problem Statement

Rapid urbanization has resulted in:

- Rising urban temperatures
- Loss of vegetation cover
- Increased energy consumption
- Heat-related public health risks
- Reduced climate resilience

GeoThermX addresses these challenges by providing intelligent heat mapping, hotspot detection, predictive modeling, and cooling intervention simulations.

---

## ✨ Key Features

### 🔥 Urban Heat Hotspot Detection
Detect and visualize urban regions experiencing extreme thermal stress using environmental and geospatial datasets.

### 🤖 AI-Powered Climate Intelligence
Integrated Gemini AI agent generates comprehensive climate insights, risk assessments, and actionable recommendations.

### 🌱 Cooling Intervention Simulator
Simulate and evaluate the impact of:

- Tree plantation drives
- Cool roof implementations
- Surface albedo enhancement
- Urban greening initiatives

### 🧠 Machine Learning Predictions
Predict Land Surface Temperature (LST) using a Random Forest-based model trained on multiple environmental parameters.

### 🗺️ Interactive GIS Dashboard
Visualize:

- Urban heat hotspots
- Temperature distributions
- Environmental indicators
- Simulation outcomes
- AI-generated reports

### 📊 Explainable AI Analytics
Analyze the influence of environmental variables through feature importance and model interpretation.

---

## 🛰️ Environmental Parameters

| Parameter | Description |
|------------|------------|
| LST | Land Surface Temperature |
| NDVI | Vegetation Index |
| NDBI | Built-up Area Index |
| Humidity | Atmospheric Moisture |
| Wind Speed | Air Flow Intensity |
| Albedo | Surface Reflectivity |
| Tree Cover | Vegetation Percentage |
| Building Density | Urban Structural Concentration |

---

## 🏗️ System Architecture

```text
Satellite & Environmental Data
                │
                ▼
     Data Processing Pipeline
                │
                ▼
      Feature Engineering
                │
                ▼
      Random Forest Model
                │
     ┌──────────┼──────────┐
     ▼          ▼          ▼
 Hotspot   Cooling     Gemini AI
Detection Simulation   Analysis
     │          │          │
     └──────────┼──────────┘
                ▼
       Interactive Dashboard
```

---

## 🛠️ Technology Stack

### Frontend
- React 19
- Vite
- React Leaflet
- Chart.js
- Axios

### Backend
- FastAPI
- Uvicorn
- Python 3.11+

### Machine Learning & AI
- Scikit-Learn
- NumPy
- Pandas
- Google Gemini API

### Geospatial Analytics
- GIS Mapping
- Spatial Analysis
- Heatmap Visualization

---

## 📂 Project Structure

```text
GeoThermX/
│
├── Backend/
│   ├── main_advanced-1.py
│   ├── gemini_agent.py
│   ├── get_temperature.py
│   ├── merge_tiles.py
│   └── prepare_data.py
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/GeoThermX.git
cd GeoThermX
```

### Backend Setup

```bash
cd Backend
pip install -r requirements.txt
uvicorn main_advanced-1:app --reload
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📡 API Endpoints

| Endpoint | Method | Purpose |
|-----------|---------|----------|
| `/` | GET | Health Check |
| `/train-model` | POST | Train ML Model |
| `/predict-temperature` | POST | Temperature Prediction |
| `/detect-hotspots` | GET | Heat Hotspot Detection |
| `/simulate-cooling` | POST | Cooling Simulation |
| `/heatmap-data` | GET | Heatmap Visualization Data |
| `/feature-importance` | GET | Model Explainability |
| `/gemini-spatial-analysis` | GET | AI Climate Insights |

---

## 📈 Applications

### 🏙️ Smart City Planning
Enable sustainable urban infrastructure development.

### 🌳 Urban Greening Strategies
Identify optimal regions for tree plantation and green infrastructure.

### 🌍 Climate Resilience
Support long-term climate adaptation and heat mitigation planning.

### 📋 Policy Support
Generate AI-powered recommendations for government agencies and municipalities.

### 🛰️ Environmental Monitoring
Track and analyze thermal stress across urban landscapes.

---

## 🔮 Future Scope

- Real-time satellite data integration
- Multi-city deployment
- Advanced climate forecasting
- Carbon footprint estimation
- Mobile application development
- Earth Observation data integration
- AI-driven urban planning recommendations

---

## 👨‍💻 Team GeoThermX

| Name | Role |
|--------|--------|
| **Kunal Srivastava** | AI/ML Development, Backend Engineering, Geospatial Analytics | [LinkedIn](https://linkedin.com/in/kunal-srivastava8810) |
| **Shivam Gupta** | Full Stack Development, System Architecture, Integration | [LinkedIn](https://linkedin.com/in/shivam-gupta-969397321) |
| **Kumar Ankit** | Research, Data Processing, Frontend Visualization | [LinkedIn](https://linkedin.com/in/kumar-ankit-943b18418) |


---

## 🏆 Bharatiya Antariksh Hackathon 2026

**Project Title:** GeoThermX – AI-Powered Urban Heat Island Intelligence & Mitigation Platform

**Team:** GeoThermX

**Domain:** Artificial Intelligence × Remote Sensing × Climate Technology × Smart Cities

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project has been developed solely for educational, research, innovation, and hackathon purposes.

---

<div align="center">

### 🌎 Building Cooler Cities with AI & Geospatial Intelligence

#### "From Satellite Data to Sustainable Decisions"

</div>
