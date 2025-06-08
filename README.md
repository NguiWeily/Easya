# 🌐 SeamlessCross: Ripple-Powered Global Transfers

> Built for the Ripple x EasyA Singapore Hackathon by Team J-W

## 🚀 Overview

SeamlessCross enables lightning-fast, secure cross-border payments using the XRP Ledger. This project features OTP-verified transactions, multi-currency support, and real-time analytics. 
Slides: https://www.canva.com/design/DAGpu5p2ekQ/1HgGk6mbwtUnMIzyaRTn_Q/edit?utm_content=DAGpu5p2ekQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 
Video: https://youtu.be/Rz8vfrOt7Mo

## 🧱 Tech Stack

- Frontend: React + Tailwind CSS
- Backend: Flask (Python)
- PDF Generation: FPDF
- Communication: REST API + Axios

---

## 🖥️ Setup Instructions

### Backend (Flask API)
```bash
cd backend
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### Frontend (React App)
```bash
cd frontend
npm install
npm start
```

### Access URLs
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

---

## ✨ Features

- 🔒 OTP-authenticated transactions
- 💱 Multi-currency support: USD, EUR, SGD
- 📊 Live transaction analytics
- 📄 PDF receipts
- 📱 Mobile responsive UI
- 🔗 QR-code support (coming soon)

---

## 📂 Folder Structure

```
SeamlessCrossDemo/
├── backend/
│   ├── app.py
│   └── requirements.txt
└── frontend/
    ├── src/
    │   ├── App.js
    │   └── index.js
    ├── public/
    │   └── index.html
    └── package.json
```

---

## 📜 License

MIT — feel free to use, modify and build upon it.
