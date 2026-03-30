# 🚀 SpaceX Falcon 9 First Stage Landing Prediction
### *Applied Data Science Capstone Project*

---

## 📋 Project Overview
The goal of this project is to predict whether the **first stage of a SpaceX Falcon 9 rocket** will land successfully. 

**Why it matters?**  
SpaceX advertises Falcon 9 rocket launches on its website with a cost of **$62 million**; other providers cost upward of **$165 million** each. Much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch.

---

## 🛠 Project Pipeline

### 🔍 1. Data Collection & Wrangling
*   **API & Web Scraping:** Gathering data via the SpaceX API and scraping Wikipedia for booster details.
*   **Data Cleaning:** Handling missing values, filtering for Falcon 9, and one-hot encoding categorical variables.

### 📊 2. Exploratory Data Analysis (EDA)
*   **SQL Queries:** Executing queries to gain initial insights into landing success rates and payload masses.
*   **Visualization:** Using `Matplotlib` and `Seaborn` to analyze relationships between flight number, launch sites, and orbits.

### 🗺️ 3. Interactive Visual Analytics
*   **Folium:** Building interactive maps to visualize launch site proximity to coastlines and highways.
*   **Plotly Dash:** Developing a real-time dashboard to filter data by launch site and payload range.

### 🤖 4. Machine Learning Prediction
Training and optimizing classification models using **GridSearchCV**:
*   `Logistic Regression`
*   `Support Vector Machine (SVM)`
*   `Decision Tree`
*   `K-Nearest Neighbors (KNN)`

### 📈 5. Storytelling & Reporting
*   Synthesizing findings into a final presentation to communicate data-driven insights to stakeholders.

---

## 🧰 Tech Stack

| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Analysis** | Pandas, NumPy, SQL (SQLite) |
| **Visualization** | Matplotlib, Seaborn, Folium |
| **Machine Learning** | Scikit-learn (GridSearchCV) |
| **Web Apps** | Plotly Dash, Beautiful Soup (Scraping) |

---

## 📂 Repository Structure
```text
├── data/               # CSV datasets (raw and processed)
├── notebooks/          # Jupyter Notebooks for each stage
├── presentation/       # Final PDF/PPTX report
└── README.md           # Project documentation
