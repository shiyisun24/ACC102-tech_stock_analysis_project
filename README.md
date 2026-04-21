#ACC102 Mini Assignment – Track 2
#US Tech Stock Data Analysis Project

---
## 📌 Project Overview 
This project conducts a comprehensive, systematic data analysis of the stock market performance and financial health of three leading U.S. technology companies: Apple (AAPL), Microsoft (MSFT), and Google (GOOGL) over the period from 2020 to 2025. Using real and reliable financial data retrieved from the WRDS database (CRSP and Compustat), the project implements a complete end-to-end analytical workflow in Python, including data extraction, cleaning, processing, statistical calculation, professional visualization, and deep interpretation. The analysis evaluates stock price trends, monthly returns, investment risk levels, and core financial ratios such as PE ratio, ROA, and debt-to-asset ratio, aiming to reveal the long-term growth patterns, profitability, stability, and financial structure of leading tech enterprises. This project provides a fully reproducible, academically rigorous, and practically valuable analysis template suitable for finance learning, investment reference, and data analysis demonstration.

## 🎯 Purpose & Target Audience 
### Analysis Purpose
1. To observe and compare long-term stock price trends and monthly return patterns of AAPL, MSFT, and GOOGL from 2020 to 2025.
2. To evaluate investment risk and stability by analyzing return volatility (standard deviation).
3. To analyze corporate financial health by calculating and interpreting key financial ratios, including PE ratio, ROA, and debt-to-asset ratio.
4. To identify post-pandemic performance trends and recovery patterns in the global technology sector.
5. To demonstrate a complete, standardized financial data analysis workflow using Python and WRDS.

### Target Audience
- Finance and accounting students learning quantitative analysis and stock research
- Individual investors and beginners interested in tech stock performance
- Users learning financial data processing, pandas, and data visualization
- Educational and academic users seeking a clear, replicable data analysis framework

## 📊 Data Source
- Database: WRDS CRSP (stock price & monthly return) + Compustat (financial statements)
- Access Date: April 2026
- Time Period: 2020 – 2025
- Key Variables: Date, Stock Price, Monthly Return, PE Ratio, ROA, Debt-to-Asset Ratio

## 🧰 Tools & Libraries
- Python 3
- wrds (WRDS database connection)
- pandas (data cleaning, processing, and analysis)
- matplotlib (professional visualization)
- openpyxl (Excel export)

## 📂 Files Included
- `stock_analysis.ipynb` – Main Jupyter Notebook code file
- `tech_stock_full_analysis.xlsx` – Cleaned, merged final dataset
- `price_trend.png` – Monthly stock price trend chart
- `annual_return.png` – Annual average monthly return comparison
- `volatility.png` – Stock volatility (risk level) analysis
- `financial_ratios.png` – PE, ROA, Debt-to-Asset trend charts
- `requirements.txt` – Required Python packages
- `README.md` – Full project documentation

## 🚀 How to Run
1. Install required packages:
   pip install -r requirements.txt
2. Open `stock_analysis.ipynb` using Jupyter Notebook
3. Run all cells to regenerate data, charts, and insights
4. View exported Excel file and output images

## 📈 Key Outputs
1. Stock price trend (2020–2025)
2. Annual average monthly return bar chart
3. Volatility (risk) comparison
4. Financial ratio trends: PE, ROA, Debt-to-Asset
5. Clean, structured dataset exported to Excel

## 🔍 Key Insights
- Microsoft (MSFT) shows the strongest long-term price growth and highest average monthly return.
- Apple (AAPL) has the lowest volatility and demonstrates strong investment stability.
- Google (GOOGL) maintains balanced performance between return and risk.
- All three tech stocks experienced a strong rebound after 2023.
- MSFT achieves the highest ROA, indicating strong profitability and asset efficiency.

## ⚠️ Limitations
- Only three large‑cap tech companies are included.
- Analysis uses monthly and annual frequency data.
- Financial ratios rely on Compustat data availability.
- Results reflect historical performance rather than future predictions.

## ✅ AI Disclosure
AI tools were used to assist with code formatting, visualization adjustment, and English proofreading during this project. All core logic, data analysis, workflow design, result interpretation, and project structure were independently completed, verified, and fully understood by the student.

## 📬 Student Information
- Name: [Shiyi Sun]
- Student ID: [2473063]
- Module: ACC102
- Track: Track 2 – GitHub Data Analysis Project
