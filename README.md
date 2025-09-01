# 🚗 Cars Dataset Analysis

## 📌 Project Overview
This project analyzes a dataset of cars, containing specifications such as engine size, horsepower, fuel efficiency, and pricing.  
The analysis focuses on **data cleaning, preprocessing, and extracting insights** about car manufacturers, origins, and performance.

---

## 📂 Dataset Information
- **Total Records:** 428
- **Total Features:** 15
- **Key Columns:**
  - `Make` – Manufacturer of the car
  - `Model` – Model name
  - `Type` – Car type (SUV, Sedan, etc.)
  - `Origin` – Region (Asia, Europe, USA)
  - `Horsepower` – Engine power
  - `MPG_City` / `MPG_Highway` – Fuel efficiency
  - `Weight`, `Wheelbase`, `Length` – Physical attributes
  - `MSRP`, `Invoice` – Pricing details

---

## 🛠 Data Preprocessing
1. **Handling Missing Values**
   - Filled missing values in the `Cylinders` column using the column mean.

2. **Exploratory Steps**
   - Checked unique manufacturers (`Make`) and their counts.
   - Filtered cars with `Origin` in **Asia** or **Europe**.
   - Removed cars with `Weight > 4000 lbs`.

3. **Feature Adjustment**
   - Increased all values of `MPG_City` column by 3 to simulate improved fuel efficiency.

---

## 📊 Insights
- Dataset covers a wide range of **car manufacturers** with varying representation.
- Asian and European cars form a large share of the dataset.
- Filtering out heavy cars ensures focus on consumer-level vehicles.
- Adjusted `MPG_City` demonstrates how technological improvements could impact efficiency.

---

## ✅ Conclusion
- Dataset is now **cleaned and ready** for further analysis or modeling.
- Provides a strong base for **price prediction, clustering, or trend visualization**.
- Preprocessing improved reliability and usability of the data.

---

## 🚀 Next Steps
- Perform **statistical analysis** and visualization (distributions, correlations, scatter plots).  
- Build **machine learning models** (e.g., regression for price prediction).  
- Explore **regional differences** in fuel efficiency and pricing.  
- Identify **top-performing car brands** based on horsepower and MPG.

---

## 📦 Requirements
Install the following Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn jupyter
