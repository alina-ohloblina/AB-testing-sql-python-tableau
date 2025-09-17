# AB-testing-sql-python-tableau
This project analyzes A/B test results using statistical methods in Python and visualizes key conversion metrics in Tableau. It replaces manual significance testing with a scalable, automated workflow and presents the results in an interactive dashboard.
## 📌 Project Overview

**Goal:**  
- Calculate statistical significance for conversion metrics using Python  
- Visualize results in Tableau with breakdowns by test group, country, and device

**Metrics Analyzed:**  
- `add_payment_info / session`  
- `add_shipping_info / session`  
- `begin_checkout / session`  
- `new_accounts / session`

---

## 🧠 Methodology

### Stage 1: Python Significance Calculation
- Data extracted via SQL from BigQuery
- Calculations performed in Google Colab using proportions z-test
- Loop-based logic to handle multiple metrics and breakdowns
- Output saved as CSV for Tableau visualization

📎 [Google Colab Notebook]([link-to-your-notebook](https://colab.research.google.com/drive/1E89zv7qKqsGzviQAUR131QdmUXZqeL2C#scrollTo=ZZCZolwgepQK))  


---

### Stage 2: Tableau Visualization
- Dashboard redesigned with new layout and color palette
- Displays conversion rates and significance flags
- Includes filters by test number, country, and device
- Text explanation of Python logic included
- 
This is a link to my dashboard:
  https://public.tableau.com/app/profile/alina.ohloblina/viz/ABtestingoverview/Dashboard1
Short overview:
  <img width="1794" height="998" alt="image" src="https://github.com/user-attachments/assets/cca4ec06-402b-4500-a9ee-bc067f7ce77d" />
