# Internship Data Analysis Project

## 📌 Project Overview
This project focuses on analyzing real-world internship data to extract meaningful insights related to internship trends such as stipend distribution, skill demand, popular roles, and location-wise opportunities.  
The project demonstrates an end-to-end data analytics workflow using **Python (Pandas)** and **MySQL**.

---

## 🛠 Tools & Technologies Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- MySQL & MySQL Workbench
- GitHub

---

## 📂 Dataset Description
The dataset contains internship listings with the following attributes:
- Internship ID
- Role
- Company Name
- Location
- Duration
- Stipend
- Internship Type
- Skills Required
- Perks
- Hiring Since
- Number of Openings
- Number of Applications
- Website Link

Two versions of the dataset are maintained:
- `internships_raw.csv` – Original dataset
- `internships_cleaned.csv` – Cleaned and processed dataset

---

## 🧹 Data Cleaning & Preprocessing
Data cleaning was performed using **Python (Pandas)** in Jupyter Notebook:
- Removed duplicate records
- Standardized column names (lowercase, snake_case)
- Converted stipend values into numeric format using regex
- Handled missing values logically (e.g., skills and perks filled as *Not specified*)
- Verified data types and data consistency

All cleaning steps are documented in:
