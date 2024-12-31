# :rocket: Applied Data Science Capstone: SpaceX Rocket Landing Prediction

### Project Overview

SpaceX revolutionized space travel with its affordable launch costs thanks to reusable Falcon 9 rockets. Predicting the reusability of the first stage helps estimate launch costs. By leveraging machine learning and publicly available data, this project aims to build a model that predicts successful first-stage landings.

### Key Questions

* How do payload mass, launch site, flight history, and orbital parameters influence landing success?
* Has the landing success rate improved over time?
* What machine learning algorithm is best suited for this binary classification task?

### ️ Methodology

1. **Data Acquisition:**
    * We retrieved data from the SpaceX REST API and Wikipedia web scraping.
2. **Data Wrangling:**
    * Data was filtered, missing values addressed, and one-hot encoded for binary classification.
3. **Exploratory Data Analysis (EDA):**
    * We visualized and analyzed the data using both traditional methods and SQL.
4. **Interactive Visual Analytics:**
    * Interactive visualizations were created using Folium and Plotly Dash.
5. **Predictive Modeling:**
    * Classification models were built, tuned, and evaluated to achieve optimal performance in predicting landing success.

This project demonstrates a complete data science workflow, from data acquisition to predictive modeling.
