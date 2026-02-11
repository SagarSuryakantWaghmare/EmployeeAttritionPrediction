# Employee Attrition Prediction

A full-stack machine learning application that predicts employee attrition and provides actionable HR analytics insights.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![React](https://img.shields.io/badge/React-18-61DAFB)
![Flask](https://img.shields.io/badge/Flask-2.0+-black)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

Employee attrition is a significant challenge for organizations, leading to increased recruitment costs and decreased productivity. This application uses machine learning to:

- Predict which employees are at risk of leaving
- Identify key factors contributing to attrition
- Provide data-driven insights for retention strategies

## Demo

| Feature | Description |
|---------|-------------|
| Prediction | Input employee details to get real-time attrition risk predictions |
| Insights | Interactive visualizations of attrition patterns and trends |
| Analytics | Understand factors like job satisfaction, salary, and work environment |

## Tech Stack

### Backend
- **Flask** - REST API framework
- **scikit-learn** - Machine learning model
- **pandas** - Data processing
- **NumPy** - Numerical computing

### Frontend
- **React** - UI framework
- **Material-UI** - Component library
- **Chart.js** - Data visualizations
- **Axios** - API client

## Quick Start

### Prerequisites
- Python 3.8+
- Node.js 16+
- npm or yarn

### Backend Setup

```bash
cd server
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python train_model.py
python app.py
```

### Frontend Setup

```bash
cd client
npm install
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## Project Structure

```
EmployeeAttritionPrediction/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   └── services/       # API service layer
│   └── package.json
│
├── server/                 # Flask backend
│   ├── api/                # REST API endpoints
│   ├── models/             # ML prediction models
│   ├── data/               # Dataset storage
│   ├── data_analysis/      # Analytics module
│   └── requirements.txt
│
└── README.md
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/features` | Get required features for prediction |
| POST | `/api/predict` | Predict attrition for an employee |
| GET | `/api/insights` | Get analytics and insights |

## Dataset

This project uses the IBM HR Analytics Employee Attrition dataset containing employee information such as:
- Demographics (Age, Gender, Education)
- Job details (Department, Role, Salary)
- Satisfaction metrics (Job, Environment, Work-Life Balance)
- Performance indicators

## License

Copyright © 2026 Sagar Suryakant Waghmare

## Author

**Sagar Suryakant Waghmare**

[![GitHub](https://img.shields.io/badge/GitHub-SagarSuryakantWaghmare-181717?logo=github)](https://github.com/SagarSuryakantWaghmare)
