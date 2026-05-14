# advanced-ai-demand
I Demand Forecasting System
An AI-powered full-stack web application that forecasts future product demand using historical sales datasets and provides business analytics through an interactive dashboard.

Features
Authentication Module
User Registration
User Login
JWT Authentication
Protected APIs
Session Handling
Dataset Upload Module
Upload CSV/Excel datasets
Data validation
Missing value handling
Duplicate record removal
Dataset storage
AI Forecasting Module
Dataset preprocessing using Pandas
Demand forecasting using Machine Learning
Future sales prediction
Forecast accuracy calculation
Dashboard & Analytics
Total Sales Analytics
Total Orders Analytics
Monthly Sales Trends
Top Products Analysis
Interactive Charts & Graphs
Reports Module
Excel Report Export
PDF Report Export
Frontend Features
Responsive UI
Protected Routes
Dynamic Dashboard
Forecast Visualization
API Integration
Tech Stack
Backend
FastAPI
MySQL
SQLAlchemy
JWT Authentication
Pandas
Scikit-learn
Frontend
React.js
Tailwind CSS
Axios
Recharts
Project Structure
AI-Demand-Forecasting/
│
├── backend/
│   ├── app/
│   │   ├── db/
│   │   ├── models/
│   │   ├── routers/
│   │   ├── schemas/
│   │   ├── utils/
│   │   └── main.py
│   │
│   ├── uploads/
│   ├── reports/
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── api/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
└── README.md
Backend Setup
1. Clone Repository
git clone <your-github-repo-link>
2. Navigate to Backend
cd backend
3. Create Virtual Environment
python -m venv venv
4. Activate Virtual Environment
Windows
venv\Scripts\activate
Mac/Linux
source venv/bin/activate
5. Install Requirements
pip install -r requirements.txt
6. Configure Environment Variables
Create .env

DATABASE_URL=mysql+pymysql://root:password@localhost:3306/forecast_db

SECRET_KEY=your_secret_key

ALGORITHM=HS256

ACCESS_TOKEN_EXPIRE_MINUTES=60
7. Run Backend Server
uvicorn app.main:app --reload
Backend runs on:

http://127.0.0.1:8000
Swagger Docs:

http://127.0.0.1:8000/docs
Frontend Setup
1. Navigate to Frontend
cd frontend
2. Install Dependencies
npm install
3. Run Frontend
npm run dev
Frontend runs on:

http://localhost:5173
API Modules
Authentication APIs
Register User
Login User
JWT Token Authentication
Dataset APIs
Upload Dataset
Dataset Validation
Forecast APIs
Generate Forecast Predictions
Dashboard APIs
Sales Analytics
Monthly Trends
Reports APIs
Export Excel Report
Export PDF Report
Forecasting Workflow
Upload sales dataset
Clean and preprocess data
Train forecasting model
Generate future demand predictions
Visualize analytics and forecast charts
Export reports
Screenshots
Register Page
Register Page

Login Page
Login Page

Dashboard
Dashboard

Dataset Upload
upload

Forecast Visualization
Forecast

Reports Module
reports

Swagger API Documentation
docs

Future Improvements
Prophet Forecasting Integration
Dark Mode
Advanced Analytics
Forecast History
Docker Deployment
Cloud Deployment
Email Reports
Author
Manikandan S

License
This project is developed for learning and portfolio purposes.

About
AI-powered demand forecasting system using FastAPI, React, Machine Learning, MySQL, and analytics dashboard.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
1
@Manikandan-r
Manikandan-r
Languages
JavaScript
55.2%
 
Python
43.8%
 
Other
1.0%
Footer
