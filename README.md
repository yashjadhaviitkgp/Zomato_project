# 🍽️ Zomato Data-Driven Restaurant Success Forecast

This project leverages real-world Zomato restaurant data to forecast the success of restaurants in Bengaluru using exploratory data analysis, NLP techniques, and machine learning.

## 📌 Overview

With over 57,000 restaurant entries, this project analyzes various features such as location, rating, cost, cuisine, and user reviews to predict the likelihood of success for a restaurant. The core idea is to empower restaurant owners and food entrepreneurs with data-backed insights to make better business decisions.

## 🔍 Objectives

- Perform data cleaning and preprocessing on Zomato's Bengaluru restaurant dataset.
- Conduct exploratory analysis to uncover trends and correlations.
- Visualize popular cuisines and liked dishes using WordCloud.
- Build a predictive model using Random Forest to forecast restaurant success.

## 🛠️ Tools & Technologies

- Languages: Python
- Libraries: `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `Scikit-learn`, `WordCloud`, `SQLite3`, `BeautifulSoup` (if applicable)
- Model: Random Forest Classifier

## 📊 Key Insights

- Analyzed over 20,639 liked dishes using a WordCloud to enhance menu strategies.
- Identified location and cuisine-based trends influencing customer ratings.
- Achieved 91.5% accuracy in success prediction using a Random Forest model.

## 🔧 Features

- 📈 EDA with visualizations on cost, ratings, location density, and service type.
- ☁️ WordCloud to visualize most popular dishes across restaurants.
- 🔍 Success forecasting based on key features using a supervised ML model.

## 📂 Folder Structure


## 🧠 How It Works

1. Data Loading & Cleaning
   - Handled null values, duplicates, and inconsistent formats.
2. Exploratory Data Analysis (EDA)
   - Seaborn & matplotlib used for plotting relationships and distributions.
3. NLP WordCloud
   - Created from `dish_liked` column to identify popular items.
4. Predictive Modeling
   - Target variable: Success (e.g., rating > 3.5).
   - Model: Random Forest classifier with optimized parameters.
   - Evaluation: Accuracy, confusion matrix, classification report.

## 💡 Outcomes

- Helped define a data-driven menu optimization strategy.
- Provided a success likelihood prediction model for restaurant profiling.
- Supported strategic planning for location-based food businesses.

## 🚀 Future Work

- Integrate real-time Zomato API for live data.
- Deploy as a web app using Flask or Streamlit.
- Add feature for cost-to-revenue forecasting.

## 🤝 Acknowledgments

Thanks to [Zomato](https://www.zomato.com) and open-source contributors for making this dataset available for educational use.

---

Author: Yash Jadhav  
Institute: IIT Kharagpur  
