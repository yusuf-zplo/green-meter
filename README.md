# 🌱 Green Meter App
**Carbon Emissions Analytics for Sustainable Logistics**

Green Meter App helps logistics organizations measure their annual CO₂ emissions across transportation, equipment, buildings, and IT systems — and evaluate optimization strategies like electric vehicles and efficient flight load factors.

📊 Includes interactive charts, CO₂ reduction modeling, sliders, and clean data visualization using Flask + Plotly.

---

## 🚀 Features

✅ Per-category CO₂ calculations (Cars, Trucks, Planes, Buildings, IT, etc.)  
✅ Baseline vs Optimized emissions scenarios  
✅ EV share & KM reduction sliders for cars  
✅ Load Factor optimization for planes  
✅ Sample dataset to explore quickly  
✅ Real-time Pie + Bar charts using Plotly  
✅ Secure, modern UI in dark theme 🌙  
✅ Fully offline-capable backend calculation engine  

---

## 🧩 Technologies Used

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS (custom), JavaScript, Plotly |
| Backend | Python Flask |
| Logic | Custom CO₂ calculation engine |
| Data transport | JSON REST APIs |

---

## 📦 Project Structure

```
GreenMeterApp/
│
├── app.py
│
├── emissions_engine/
│   ├── __init__.py
│   ├── formulas.py
│   ├── sample_data.py
│
├── templates/
│   ├── layout.html
│   ├── index.html
│
├── static/
│   ├── css/style.css
│   └── js/
│       ├── api.js
│       ├── charts.js
│
├── requirements.txt
└── README.md
```

---

## 🛠 Installation & Setup

### 1️⃣ Clone this repository

```sh
git clone https://github.com/your-username/GreenMeterApp.git
cd GreenMeterApp
```

### 2️⃣ Create & activate a Virtual Environment (recommended)

**Windows**
```sh
py -3 -m venv venv
venv\Scripts\activate
```

**macOS / Linux**
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install dependencies

```sh
pip install -r requirements.txt
```

---

## ▶️ Run the App

```sh
python app.py
```

Open your browser and visit:

👉 http://localhost:5000

✅ Application should now be live!

---

## 🧪 How to Use

| Button | What it does |
|--------|--------------|
| **Load Sample** | Loads realistic logistics data and auto-calculates emissions |
| **Calculate** | Recalculates emissions based on your inputs and sliders |
| **Reset** | Clears everything to default values |

Adjust sliders for:
- EV Share (%)
- Car KM Reduction (%)
- Plane Load Factor (%)

Charts will update instantly!

---

## 🧮 Emission Formula Sources

All emission factors and formulas follow the official reference sheet used for sustainability calculations.

✅ All results shown in **tons CO₂e per year**  
✅ Sliders modify only applicable categories (Cars & Cargo Planes)

---

## 🔒 Security & Reliability

- Input validation on backend (no negative or invalid values)
- Safe JSON parsing & error handling
- Secure response headers applied after every request  

---

## ❓ Troubleshooting

| Issue | Fix |
|------|----|
| App doesn’t load | Ensure Python 3.8+ and Flask installed |
| Charts don’t update | Check browser console (F12 → Console tab) |
| API shows error popup | Check terminal logs for message |

---

## 🚧 Future Enhancements

✅ Export results to PDF/Excel  
✅ Multi-scenario comparison mode  
✅ User authentication + data saving  
✅ Light/High-contrast theme toggle  
✅ Mobile layout enhancements  

---

## 📜 License

MIT License — feel free to modify and deploy.

---

## 🤝 Contribution

Pull requests welcome!  
Please format commits clearly & document UI/logic changes.

---

### 🌍 Build Decisions Based on Data — Help Reduce Emissions Today 💚
