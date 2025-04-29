# stock-market-analysisBased on the files you've uploaded (`stock.ipynb`, `stock.csv`, and `symbols_valid_meta.csv`), here is a **customized README.md** for your **Stock Market Analysis Project**:

---

```markdown
# 📊 Stock Market Analysis Dashboard

This project is an interactive **Stock Market Analysis Dashboard** created using Python, Jupyter Notebook, and Flask. It leverages historical stock price data to visualize trends, daily changes, and correlation among multiple companies.

---

## 📁 Files Included

- `stock.ipynb` — Jupyter Notebook for analysis and dashboard integration.
- `stock.csv` — Historical stock data with columns like `Date`, `Close`, and `Company`.
- `symbols_valid_meta.csv` — Metadata file with company information (e.g., names, symbols, sectors).

---

## 🚀 Features

- 📈 **Stock Price Trends** – Line chart of closing prices over time.
- 🔁 **Daily Changes** – Percent change in closing price per company.
- 🔗 **Correlation Heatmap** – Inter-company stock price correlation using a heatmap.
- 🌐 **Web Dashboard (Flask)** – Interactive Plotly charts rendered through a Flask web app.

---

## 🛠️ Tech Stack

- **Python Libraries:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `flask`, `threading`, `os`

- **Visualization:**  
  `plotly.express`, `seaborn`, `matplotlib`

- **Web Framework:**  
  `Flask` – for serving an interactive dashboard via web browser.

---

## 📊 Dataset Format

**1. `stock.csv` includes:**

| Date       | Company | Close |
|------------|---------|-------|
| 2024-01-01 | AAPL    | 180.2 |
| 2024-01-01 | MSFT    | 310.1 |
| ...        | ...     | ...   |

**2. `symbols_valid_meta.csv` includes:**

| Symbol | Name               | Sector       |
|--------|--------------------|--------------|
| AAPL   | Apple Inc.         | Technology   |
| MSFT   | Microsoft Corp.    | Technology   |
| ...    | ...                | ...          |

---

## ▶️ How to Run the Dashboard

### 1. Install Required Packages

```bash
pip install pandas numpy flask plotly matplotlib seaborn
```

### 2. Run the Flask App

You can either run the `.ipynb` notebook or convert the relevant parts to a `.py` script. If you're using the script version:

```bash
python dashboard.py
```

### 3. Open the Browser

Go to [http://localhost:5000](http://localhost:5000) to view your dashboard.

---

## 🧠 Analysis Performed

- Conversion of date formats for time series analysis.
- Grouping and percent change computation per company.
- Correlation matrix to identify inter-stock movement relationships.
- Visual rendering using Plotly for enhanced interactivity.

---

## 📌 Future Enhancements

- Add stock filter dropdowns for user selection.
- Integrate live stock market APIs.
- Add company metadata integration on hover in charts.
- Enable download/export options for charts and data.

---

## 👩‍💻 Author

**Tanushka Tomar**  
Actively involved in tech events, led the AI Odyssey segment of the TechRhythm competition.

---

## 📄 License

This project is open-source and available under the **MIT License**.
```

---

![image](https://github.com/user-attachments/assets/20732e3b-c0e4-4d9f-98ee-a0d86a72815b)
![image](https://github.com/user-attachments/assets/abda6b94-662c-4884-b245-fd71073b0bd7)
![image](https://github.com/user-attachments/assets/a096bec8-dca4-433c-bdf4-8be90772a641)


