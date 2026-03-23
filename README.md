# 📊 DataPulse — AI-Powered Data Intelligence Dashboard

> A full-stack Python application showcasing advanced algorithms, real-time financial analytics, and interactive data visualization.

![Python](https://img.shields.io/badge/Python-3.11+-gold?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-3.0-gold?style=flat-square&logo=flask)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🚀 Features

| Feature | Description |
|---|---|
| **Geometric Brownian Motion** | Realistic stock price simulation using GBM — same model used in Black-Scholes |
| **RSI Algorithm** | Real Relative Strength Index (14-period) from scratch — no libraries |
| **QuickSort Visualizer** | Step-by-step animated algorithm visualization with speed control |
| **Anomaly Detection** | Z-score based statistical outlier detection (threshold: 2.5σ) |
| **Portfolio Analytics** | Sharpe Ratio, Herfindahl-Hirschman Index, diversification scoring |
| **Moving Average** | O(n) sliding window MA(20) engine |
| **REST API** | 5 clean JSON endpoints powering the entire frontend |

---

## 🧠 Algorithms Implemented

```
DataEngine
├── generate_stock_data()    → Geometric Brownian Motion (GBM)
├── compute_moving_average() → O(n) sliding window
├── compute_rsi()            → 14-period RSI (financial)
├── quick_sort_trace()       → QuickSort with step capture
├── portfolio_analysis()     → Sharpe Ratio + HHI diversification
└── anomaly_detection()      → Z-score outlier detection
```

---

## ⚡ Quick Start

```bash
# Clone the repo
git clone https://github.com/yourname/datapulse.git
cd datapulse

# Install dependencies
pip install -r requirements.txt

# Run the server
python app.py

# Open in browser
open http://localhost:5000
```

---

## 📁 Project Structure

```
DataPulse/
├── app.py              ← Python backend (Flask + algorithms)
├── requirements.txt
├── templates/
│   └── index.html      ← Full-stack frontend (HTML/CSS/JS)
└── README.md
```

---

## 🛠 Tech Stack

- **Backend**: Python 3.11, Flask 3.0
- **Algorithms**: Pure Python (no NumPy/Pandas — all from scratch)
- **Frontend**: Vanilla JS, Chart.js, premium CSS with CSS variables
- **Design**: Obsidian-Gold luxury dark theme, DM Mono + Syne typography

---

## 📈 API Endpoints

| Endpoint | Method | Description |
|---|---|---|
| `/api/stocks` | GET | 5 stocks × 90-day price history + RSI + MA + anomalies |
| `/api/portfolio` | GET | Holdings with Sharpe ratio + diversification analysis |
| `/api/sort-viz` | GET | QuickSort steps for visualization |
| `/api/metrics` | GET | System KPI metrics |

---

## 💡 Resume Highlights

- Implemented **6 algorithms from scratch** — no NumPy or Pandas
- Built a **full-stack Python web app** with REST API architecture
- Applied **real financial models** (GBM, Black-Scholes-adjacent RSI)
- Designed a **premium UI/UX** with custom animations and responsive layout
- Demonstrated knowledge of **time/space complexity** (O(n log n) QuickSort)

---

*Built by [Your Name] · 2025*
