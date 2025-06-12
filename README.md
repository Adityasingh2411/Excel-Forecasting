# 📊 Small Shop Finance Data Forecasting

This Excel-based financial forecasting project is designed for small retail businesses to estimate future income, expenses, and net profitability. It includes dynamic models to simulate **Base**, **Best**, and **Worst Case Scenarios**, helping in data-driven decision-making.

---
## 🧠 Data Origin

The dataset used in this project was **synthetically generated using ChatGPT** based on realistic small-shop financial patterns. It is designed to mimic the operations of a small multi-outlet retail business for training and analytical demonstration purposes.

---
## 🗂️ Project Structure

### 📁 Sheets Overview

- **Raw_Data**: (Optional for extension) Placeholder for source data, e.g., historical income and expense records.
- **Yearly_Summary**: Summary view of income and expenses by year.
- **Forecast_Expenses**: Contains projected expenses under:
  - **Base Case**
  - **Best Case**
  - **Worst Case**
- **Forecast_Income**: Income forecast using the `TREND()` function under all three scenarios.
- **Income Statement**: Automatically calculates:
  - Revenue
  - COGS (as % of Revenue)
  - Operating Expenses (broken down into categories)
  - Operating Income
  - Net Income after taxes

---

## 📈 Key Features

- ✅ **Scenario Planning**: Easily switch between Best, Base, and Worst scenarios.
- 📉 **Trend Forecasting**: Uses Excel's `TREND()` function for income projections.
- 🔁 **Dynamic Cost Modeling**:
  - COGS: 30% of revenue
  - Other Income/Expense: 2.5%
  - Taxes: 25%
- 🔧 **Modular Design**: Easily update assumptions and drivers to reflect real-world changes.
- 📊 **Multi-Outlet Support**: Includes setup to filter by individual outlet or view consolidated data.


---

## ⚙️ How to Use

1. **Enter Historical Data** in `Forecast_Income` and `Forecast_Expenses`.
2. **Adjust Scenario Slider** (cell `C2` in the `Income Statement` sheet) to toggle scenarios:
   - `1` = Base
   - `2` = Best
   - `3` = Worst
3. **Update Assumptions** in the right-hand section of `Income Statement`:
   - COGS %
   - Other Income/Expense %
   - Tax %
4. View results in the dynamically updated **Income Statement**.

---


## 📌 Author

**Aditya Singh**  
Aspiring Data Analyst | Excel Modeling | Financial Forecasting

