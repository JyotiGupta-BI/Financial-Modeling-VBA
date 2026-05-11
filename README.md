# Financial-Modeling-Toolkit

A VBA-powered financial modeling engine with **Discounted Cash Flow (DCF)**, **Monte Carlo Simulation**, 
and **Scenario Analysis**, complete with reporting, error logging, and an interactive user interface.

---

## 📌 Overview
This project provides a **financial modeling toolkit** built in Excel VBA.  
It allows analysts to:
- Run deterministic **DCF valuations**.
- Perform stochastic **Monte Carlo simulations**.
- Test assumptions with **Scenario Analysis** (Base, Best, Worst cases).
- Export polished reports to PDF.
- Track errors and calculations for transparency.

---

## ✨ Features
- **[DCF Valuation](ca://s?q=Discounted_Cash_Flow_analysis)** → Calculates intrinsic value based on discounted cash flows.  
- **[Monte Carlo Simulation](ca://s?q=Monte_Carlo_simulation_in_finance)** → Runs thousands of trials with randomized inputs to produce an average valuation.  
- **[Scenario Analysis](ca://s?q=Scenario_analysis_in_finance)** → Tests Base, Best, and Worst cases with adjusted assumptions.  
- **Error Logging** → Captures errors with timestamp, procedure, and description in `ErrorLog` sheet.  
- **Reporting** → Auto-formatted `Report` sheet exported to PDF.  
- **Interactive Form** → User-friendly interface with tooltips and results grid.  

---

## ⚙️ Installation
1. Open Excel → Press `ALT + F11` to open VBA editor.  
2. Import modules
3. Insert a UserForm
4. Add sheets

---

## 🚀 Usage
- Enter inputs in the form.  
- Click All the buttons → Grid shows DCF, Monte Carlo, and Scenario Analysis results.  
- Click **Export Report** → Generates a formatted Excel sheet and PDF.  
- Hover over buttons → Tooltips explain each analysis.  

---

## 📊 Scenario Analysis Cases

| Case        | Revenue Adjustment | Expense Adjustment | Growth Adjustment | Purpose                |
|-------------|--------------------|--------------------|------------------|------------------------|
| **Base**    | No change          | No change          | No change        | Expected forecast      |
| **Best**    | +10%               | –10%               | +2%              | Optimistic assumptions |
| **Worst**   | –10%               | +10%               | –2%              | Conservative scenario  |

👉 These ranges are illustrative defaults. In practice, adjust based on industry volatility, historical performance, and risk appetite.

---

## 🛡️ Error Logging
- All errors are logged in the `ErrorLog` sheet.  
- Columns: **Timestamp**, **Procedure**, **Error Description**.  
- Ensures transparency and easier debugging.

---

## 📑 Reporting
- Results written to `Report` sheet.  
- Result generated to pdf
