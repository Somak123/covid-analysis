# 🦠 COVID-19 India Analysis

A simple data analysis project exploring the COVID-19 situation in India using **Pandas** and **Matplotlib**.  
This is part of my **open-source ML warm-up** before contributing to larger projects.

---

## 📊 Project Overview
In this project, I:
- Loaded the global COVID-19 dataset from [Our World in Data](https://ourworldindata.org/coronavirus)
- Filtered data for **India**
- Visualized:
  - Total cases vs total deaths over time
  - New cases vs new deaths (scatter plot)

---

## 🛠 Tech Stack
- **Python 3**
- **Pandas** – Data manipulation & cleaning
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive analysis

---

## 📂 Repository Structure
covid-analysis/
│
├── covid_india_analysis.ipynb # Main Jupyter notebook with code & plots
├── data/ # Dataset(s)
└── README.md # Project documentation

yaml
Copy
Edit

---

## 📸 Sample Plots
### Total Cases & Deaths Over Time
![Total Cases vs Deaths](assets/total_cases_deaths.png)

### New Cases vs New Deaths
![New Cases vs New Deaths](assets/new_cases_deaths.png)

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Somak123/covid-analysis.git
   cd covid-analysis```

2. Install dependencies:
```conda create -n covid-analysis python=3.10
conda activate covid-analysis
pip install -r requirements.txt```

3. Open the Jupyter Notebook:
  jupyter notebook covid_india_analysis.ipynb
