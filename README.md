🚀 SpaceX Falcon 9 Rocket Landing Prediction – Data Science Capstone
A machine learning pipeline built to predict the success of SpaceX Falcon 9 first-stage landings using publicly available data from the SpaceX API and Wikipedia. This capstone project was developed as part of the IBM Data Science Specialization.

📌 Project Objective
SpaceX significantly reduces launch costs by reusing the Falcon 9's first stage. Predicting the likelihood of a successful landing can offer critical insights for stakeholders and competitors.
This project answers:

What factors determine a successful rocket landing?

How do different features interact to impact landing success?

What are the best operating conditions for a successful launch?

🧠 Methodology
Data Collection:

Used SpaceX REST API

Web scraped Falcon 9 launch records from Wikipedia using BeautifulSoup

Data Wrangling:

Cleaned and merged data, handled missing values

Performed one-hot encoding for categorical features

Exploratory Data Analysis (EDA):

Visualized relationships between payload, orbit type, launch sites, and outcomes

Used SQL and PostgreSQL for deeper data insights

Interactive Visualizations:

Built a map using Folium to analyze launch site proximity

Created an interactive dashboard with Plotly Dash for user-driven exploration

Machine Learning Pipeline:

Applied Decision Tree, Logistic Regression, and KNN classifiers

Used GridSearchCV for hyperparameter tuning

Achieved best accuracy with the Decision Tree Classifier

📊 Key Insights
Higher flight numbers generally correlate with greater landing success

Specific orbits (e.g., ES-L1, GEO, SSO) have higher success rates

Payload and launch site combinations strongly affect landing outcome

Launch site KSC LC-39A has the highest success rate at 76.9%
