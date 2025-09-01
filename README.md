# 🖥️ Server Health Dashboard

A real-time **Flask-based system monitoring dashboard** that displays **CPU, Memory, and Disk usage** with live charts and progress bars.  
Built with **Python (Flask, psutil)** and **Chart.js + Bootstrap** for a clean and modern UI.

---

## 🚀 Features
- 📊 Real-time monitoring of CPU, memory, and disk usage  
- ⏳ Auto-updating charts (powered by Chart.js)  
- 🎨 Responsive design with Bootstrap  
- 🔔 Threshold-based color alerts (Green = Good, Orange = Warning, Red = High)  
- ⚡ Lightweight & easy to deploy  

---

## 📸 Screenshot
![Dashboard Preview](https://github.com/RShub1105/Server-Health-Dashboard/blob/main/Screenshot%20.png)

---

## 🛠️ Tech Stack
- **Backend:** Python, Flask, psutil  
- **Frontend:** Bootstrap 5, Chart.js  
- **Server:** Runs locally or can be deployed with Docker/GitHub  

---

## 📂 Project Structure

Server-Health-Dashboard/
│── 01.App.py
│── requirements.txt
│── templates/
│ └── index.html
│── assets/
│ └── dashboard_preview.png


---

## ⚡ Installation & Usage

### 1️⃣ Clone the repo
```bash
git clone https://github.com/YOUR-USERNAME/Server-Health-Dashboard.git
cd Server-Health-Dashboard
```
### 2️⃣ Install dependencies
pip install -r requirements.txt

### 3️⃣ Run the app
python 01.App.py



## 🐳 Run with Docker
docker build -t server-health-dashboard .
docker run -p 8080:8080 server-health-dashboard

## Author

Built with ❤️ by Rahul Sharma
