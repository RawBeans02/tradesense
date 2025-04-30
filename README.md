# 📈 TradeSense

**TradeSense** is a modular trading dashboard built using **Flask** (backend) and **React** (frontend).  
This project will eventually evolve into a full-featured quant research and trading platform, combining price-based models, macroeconomic signals, and sentiment-driven insights.

## 🔧 Current Features

- 📊 Stock charting with price history
- ⚙️ Modular backend (Flask) and frontend (React) structure
- 🚀 Ready for expansion: sentiment, macro, and AI model integration

## 🗂️ Project Structure

```
tradesense/ ├── backend/ # Flask backend │ ├── app/ │ │ ├── routes.py # API routes (e.g., /api/stock/AAPL) │ │ └── services/ # Data logic (e.g., stock_service.py) │ └── run.py # Entry point ├── frontend/ # React frontend │ ├── src/ │ │ ├── components/ # StockChart, StockTable, etc. │ │ ├── pages/ # Home.js │ │ └── services/ # Axios API wrapper
```

## 🛠️ Setup Instructions

### 1. Backend (Flask)

```bash
cd backend
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python run.py
