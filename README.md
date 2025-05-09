# 🚀 SpaceX Falcon 9 Landing Prediction – Data Science Capstone

This project is part of the **IBM Data Science Capstone** on Coursera. The objective is to build a machine learning pipeline to predict whether the **first stage of a SpaceX Falcon 9 rocket will land successfully**, which is critical to reducing launch costs.

## 📌 Project Overview

SpaceX’s ability to reuse rocket stages drastically reduces launch costs. By analysing launch data, we aim to predict the landing outcome and understand what factors contribute to a successful recovery.

## 🔍 Objectives

- Determine the factors that influence rocket landing success.
- Explore interactions between payload, orbit, and launch site.
- Build and evaluate machine learning models for predictive accuracy.

## 🧰 Tools & Technologies

- **Languages**: Python, SQL
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Folium, BeautifulSoup
- **Frameworks**: Plotly Dash
- **Databases**: PostgreSQL
- **Data Sources**: SpaceX API, Wikipedia (Web Scraping)

## 📊 Methodology

### 🛰 Data Collection
- Fetched real-time launch data via **SpaceX API**.
- Web scraped historical Falcon 9 launch data from Wikipedia using **BeautifulSoup**.

### 🧹 Data Wrangling
- Cleaned and preprocessed data.
- One-hot encoded categorical variables.
- Created binary labels for landing success.

### 📈 Exploratory Data Analysis (EDA)
- Visualised trends in launch site performance, orbit types, payload influence, and time-based patterns.
- Used SQL to query payload stats, success/failure rates, and launch outcomes.

### 🌍 Geospatial Analysis
- Mapped all launch sites using **Folium**.
- Analysed launch site proximity to railways, highways, and coastlines.

### 📊 Dashboard
- Created an interactive dashboard with **Plotly Dash** to visualise launch success by site, payload mass, and booster version.

### 🤖 Predictive Modeling
- Built several classifiers (Logistic Regression, Decision Tree, Random Forest, etc.).
- Tuned hyperparameters using **GridSearchCV**.
- Achieved highest accuracy using a **Decision Tree Classifier**.

## 🧠 Key Insights

- Launch sites with higher flight numbers tend to have greater success rates.
- KSC LC-39A had the highest launch success ratio.
- Orbit types ES-L1, GEO, HEO, SSO, and VLEO showed high success rates.
- Payload mass and orbit type significantly affect landing outcome.
- The Decision Tree classifier showed the best performance among all models.

## 📂 Project Notebooks

- [Data Collection – API](https://github.com/Vachan1603/testrepo/blob/main/jupyter-labs-spacex-data-collection-api.ipynb)  
- [Web Scraping](https://github.com/Vachan1603/testrepo/blob/main/jupyter-labs-webscraping.ipynb)  
- [Data Wrangling](https://github.com/Vachan1603/testrepo/blob/main/labs-jupyter-spacex-Data%20wrangling.ipynb)  
- [EDA & Visualization](https://github.com/Vachan1603/testrepo/blob/main/edadataviz.ipynb)  
- [SQL Analysis](https://github.com/Vachan1603/testrepo/blob/main/jupyter-labs-eda-sql-coursera_sqllite.ipynb)  
- [Dashboard with Plotly Dash](https://github.com/Vachan1603/testrepo/blob/main/IBM-Data-Science-Capstone-SpaceX.py)  

## 🏁 Conclusion

This project demonstrates the power of data-driven decision-making in aerospace. The predictive model and dashboard can serve as valuable tools for competitors looking to analyse or challenge SpaceX’s launch capabilities.

---

## 📧 Contact

**Vachan Padival**  
📍 AIML @ BNMIT  
🔗 [LinkedIn](https://www.linkedin.com/in/vachan-padival-245346323/)  
