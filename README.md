# Zero Trust Architecture (ZTA) for Military UAV Security System

## Overview
This project implements a Zero Trust Architecture framework to secure UAV telemetry and control systems.

## Features
- JWT Authentication
- Role Based Access Control
- TLS Encrypted Communication
- AI Anomaly Detection
- Real-time Dashboard
- Secure Audit Logging

## Technologies Used
- Python
- Flask
- Flask-JWT-Extended
- Flask-SocketIO
- Scikit-Learn
- Raspberry Pi
- MPU6050
- INA219
- # UAV Dashboard

This is a minimal UAV sensor + dashboard using Flask and Flask->

## Setup (Windows PowerShell)

1. Create and activate a virtual environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Upgrade pip and install dependencies

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

3. Run the app

```powershell
python app.py

##results after the steps are completed :
## 📸 Screenshots

![Login](docs/screenshots/login.jpeg)
![Dashboard](docs/screenshots/dashboard.jpeg)
![Anomaly](docs/screenshots/anomaly.jpeg)
![Audit](docs/screenshots/audit.jpeg)
![RBAC](docs/screenshots/rbac.jpeg)
![XAI](docs/screenshots/xai.png)
