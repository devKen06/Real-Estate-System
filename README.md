# Real-Estate-System

This is a capstone project developed by Mark Kenneth Facun and Arvin C. Coronel— a full-stack real estate management system with built-in price estimation and profit forecasting using linear regression.

## 🏗️ Features

- 🔐 **Login & Registration System** (Firebase Auth)
- 🏠 **Property Listing & Management**
  - Add / Edit / Delete property data
  - Tag status (On-Progress, Signed, Closed)
- 📈 **Price Estimation Module**
  - Predict future property price using `Y = a + bX` linear regression
  - Calculates ROI and projected profit
  - Line chart visualization (Chart.js)
- ☁️ **Firebase Firestore Integration**
- 📊 **Dashboard & Analytics**
- 🔒 User access security with Firestore rules

## 📂 Project Structure
real-estate-system/
├── index.html
├── register.html
├── dashboard.html
├── property.html
├── estimation.html
├── /assets/
│ ├── style.css
│ └── logo.png
├── /scripts/
│ ├── firebase-config.js
│ ├── property.js
│ └── estimation.js
├── README.md
└── .gitignore

## 🛠️ Tech Stack

- HTML / CSS / JavaScript
- Firebase (Auth + Firestore)
- Chart.js
- Git & GitHub

## 📦 Setup Instructions

1. Clone the repo  
```bash
git clone https://github.com/devKen06/Real-Estate-System.git
