# Airbnb Listings – Exploratory Data Analysis (EDA)

Welcome to my Data Science Internship Project – Task 1!

This project focuses on performing **Exploratory Data Analysis (EDA)** on a real-world dataset of Airbnb listings. The dataset used contains details such as listing names, prices, host information, and more, mainly focused on New York City.

---

## 📁 Dataset

- **Source**: Airbnb Open Data
- **File Used**: `Airbnb_Open_Data_Sample_10k.csv` (sample of 10,000 rows to stay within GitHub limits)

---

## 📊 Task Overview

**Task 1: EDA and Visualization**

### ✅ Steps Followed:

1. **Load the Dataset**  
   - Used `pandas` to load and explore the structure of the data.

2. **Data Cleaning**  
   - Handled missing values using imputation/removal.
   - Removed duplicates.
   - Detected and managed outliers using visual and statistical methods.

3. **Data Visualization**  
   - Bar charts for categorical columns like `neighbourhood group`, `room type`, etc.
   - Histograms for numeric distributions such as `price`, `availability_365`, etc.
   - Correlation heatmap for numeric features.

4. **Insights & Observations**  
   - Documented key trends, outliers, and data quality concerns.

---

## 📂 Files in This Repo

| File Name                        | Description                                      |
|----------------------------------|--------------------------------------------------|
| `Airbnb_Open_Data_Sample_10k.csv` | Sample dataset for analysis                      |
| `EDA.ipynb`                      | Jupyter Notebook with EDA, visuals & insights    |
| `requirements.txt`              | Python dependencies used                         |
| `README.md`                     | Project overview and documentation               |

---

## 🧠 Key Insights

- **Brooklyn** and **Manhattan** have the highest number of listings.
- Most listings are private rooms.
- Some extreme outliers in pricing skew the distribution.
- Several listings are inactive (zero availability or reviews).

---

## 🛠 How to Run

Make sure you have Python installed. Then:

```bash
pip install -r requirements.txt
jupyter notebook EDA.ipynb
```

---

## 📅 Deadline

> All internship tasks, including this one, are due by **28th May 2025**.

---

Thanks for checking out this project! 😊  
Feel free to explore, give feedback, or fork the repo.
