# investify-smart-finance
Investify is a Python-based desktop application built using PyQt5 that helps users manage personal finances, track expenses, monitor stock portfolios, and explore investment options — all in one place.

**Features**
 Secure Authentication – SHA-256 hashed password system
 Expense Tracking – Add expenses and visualize using pie charts
 Stock Portfolio – Track stocks with real-time price updates
 Financial News – Latest market news via News API
 Investment Modules – FD, Gold Bonds, and Stock investment simulation
 Multi-Dashboard UI – Clean and interactive user interface
 Data Storage – Lightweight CSV-based storage system

**Key Highlights**
Modular architecture with separate UI windows
Integration of real-world APIs (Alpha Vantage, News API)
Combines finance, data visualization, and GUI development
Beginner-friendly but scalable to database systems

**Tech Stack**
Language: Python
Frontend/UI: PyQt5
Data Handling: Pandas, CSV
Visualization: Matplotlib
APIs: Alpha Vantage, News API

**Project Structure**
investify/
│── app.py
│── users.csv
│── personal_finance.csv
│── fd_data.csv
│── stock_data.csv
│── gold_bond_data.csv
│── assets/ (images/icons)

**How to Run**
1. Clone Repository
git clone https://github.com/your-username/investify.git
cd investify
2. Install Dependencies
pip install pyqt5 pandas matplotlib requests
3. Run Application
python app.py

**API Setup**
Replace API keys in the code:
Alpha Vantage → https://www.alphavantage.co
News API → https://newsapi.org

**Future Improvements**
Add database (MySQL / Firebase)
Deploy as web app (Streamlit / Flask)
Add AI-based financial insights
Portfolio analytics & recommendations
