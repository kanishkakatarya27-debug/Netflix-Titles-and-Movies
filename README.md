# 🎬 Netflix Titles: Exploratory Data Analysis (EDA) Dashboard

An interactive, single-file HTML data dashboard showcasing an in-depth exploratory data analysis of the public **Netflix Titles** dataset (`8,807` records across `12` columns).

---

## 🚀 Key Highlights & Features
* **Content Mix Analysis:** Visualizes the distribution between Movies (~70%) and TV Shows (~30%).
* **Geographical Insights:** Highlights top producing countries, led by the US and India.
* **Release-Year Profiling & Outliers:** Applies IQR rules to track historical trends and manage classic content outliers.
* **Feature Engineering:** Extracts movie durations in minutes and TV show season counts using regex parsing on `date_added` and `duration` fields.
* **Predictive Trend Modeling:** Implements a least-squares linear regression trend model on 2019–2021 additions to forecast future content catalog shifts through 2024[cite: 1].
* **Data Quality Audit:** Evaluates missing values (highlighting gaps in `director`, `cast`, and `country`) and validates dataset integrity[cite: 1].

---

## 🛠️ Tech Stack & Methods
* **Data Analysis & Processing:** Python, Pandas, NumPy, Matplotlib/Seaborn[cite: 1]
* **Frontend Dashboard:** Custom HTML5, CSS3 (CSS Variables, Flexbox/Grid), and inline SVG data visualisations[cite: 1]
* **Environment:** Visual Studio Code

---

## 📁 Repository Structure
```text
├── Netflix Titles_ EDA Dashboard.html    # Interactive single-file visualization dashboard
└── README.md                             # Project documentation
