# Auto MPG Dataset — Exploratory Data Analysis (Assignment 1)

## 📌 Project Overview
This repository contains the complete submission for **Assignment 1**, focusing on a rigorous data audit, data cleaning, and exploratory analysis of the historical UCI Auto MPG dataset (398 vehicles, 1970–1982).

---

## 📁 Repository Files
* **`A1_XX_Surname.ipynb`**: Fully executed Jupyter Notebook with end-to-end Python code.
* **`A1_XX_Surname.pdf`**: Formal analytical report summarizing findings and visualizations.
* **`A1_XX_Surname_data.csv`**: Cleaned and transformed dataset exported post-audit.

---

## 🛠️ Summary of Key Steps Completed
* **Data Cleansing**: Filled 6 missing horsepower values using robust median imputation (93.5 hp). Mapped `origin` numbers to regional text labels ('USA', 'Europe', 'Japan').
* **Typo Corrections**: Fixed human data-entry spelling errors in the car name strings (e.g., *chevroelt* ➔ *chevrolet*, *toyouta* ➔ *toyota*).
* **Outlier Detection**: Used the Interquartile Range (IQR) method to locate **11 extreme horsepower outliers** (all legacy American V8 models).
* **Multicollinearity Tracking**: Used a Pearson correlation grid to discover severe data overlap ($r > 0.85$) between car weight, engine displacement, and horsepower. 

---

## 🤖 AI Disclosure
*Generative AI was used as an auxiliary tool for debugging Python code segments, structuring data cleaning steps, and refining report prose structures for professional clarity.*
