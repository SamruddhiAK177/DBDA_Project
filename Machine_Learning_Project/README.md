# 🚀 Flight Price Prediction

## 🌟 Welcome to the Flight Price Prediction Project! 🌟

This project uses data science and machine learning to predict flight ticket prices. Whether you're a traveler looking for the best deals or a student exploring machine learning, this project will help you understand how flight pricing works.

## ✈️ Introduction

Flight ticket prices change frequently due to many factors like demand, season, and airline policies. This project applies machine learning to analyze historical flight fare data and predict future prices, helping users make smarter booking decisions.

## 📌 Overview

In this project, we:

✅ **Collect & Process Data** – Scraped and cleaned flight price data from different sources.
✅ **Train a Machine Learning Model** – Built models to predict flight fares based on travel details.
✅ **Develop a Web Application** – A Flask-based interface where users can input flight details and get price predictions.
✅ **Create a Tableau Dashboard** – Provides interactive charts showing fare trends, route comparisons, and seasonal variations.

## 🚀 Features

🔹 **Data Source** – The flight price data was scraped using Selenium from [EaseMyTrip](https://www.easemytrip.com).

🔹 **Data Collection** – Gathered ticket pricing data for training the model.
🔹 **Data Exploration** – Analyzed flight data to uncover patterns and trends.
🔹 **Data Preprocessing** – Cleaned data, handled missing values, and prepared it for machine learning.
🔹 **Machine Learning Model** – Trained models to predict flight prices using real-world data.
🔹 **Model Evaluation** – Assessed model performance to ensure accurate predictions.
🔹 **Web Application** – Users can input travel details such as:

- Airline
- Source & Destination
- Travel Class
- Departure & Arrival Time
- Number of Stops
- Get a price prediction instantly!

🔹 **Tableau Dashboard** – Provides visual insights on:

- Price variations by airline
- Effect of flight duration on prices
- Seasonal changes in ticket costs
- Most frequently traveled routes

🔹 **Filling in Missing Prices** – Used the trained model to estimate missing fares in incomplete datasets.

## 🛠 Technologies Used

🔹 **Python** – For data handling, model training, and price prediction.
🔹 **Pandas & NumPy** – Used for data manipulation and analysis.
🔹 **Scikit-Learn** – Used to train and evaluate machine learning models.
🔹 **Flask** – Built a simple web application for users to interact with the model.
🔹 **Tableau** – Created interactive charts and dashboards.
🔹 **Selenium** – Automated web scraping to collect flight pricing data.
🔹 **Matplotlib & Seaborn** – Used for visualizing data trends.
🔹 **Git & GitHub** – Version control and project collaboration.

## 📊 Tableau Dashboard

Explore airfare trends and insights with our interactive Tableau dashboard.
🔗 **Live Dashboard:** [Project Dashboard](https://public.tableau.com/app/profile/samruddhi.kasar2919/viz/Project_Dashboard_17391878548390/Dashboard3?publish=yes)

### 📌 Dashboard Highlights:

🔹 **Price Trends** – See how fares change over time.
🔹 **Route Insights** – Find out which routes have the most affordable flights.
🔹 **Class Comparison** – Compare Economy, Business, and First-Class ticket prices.
🔹 **Location-Based Pricing** – View how fares vary between different cities.

## ☁️ Deployment on AWS EC2

The project has been successfully deployed on an AWS EC2 instance, making it accessible from anywhere. Users can visit the deployed application to get real-time flight fare predictions.

### Steps to Deploy on AWS EC2:

1️⃣ Launch an AWS EC2 instance and configure security groups.
2️⃣ Install required dependencies on the server:

```sh
sudo apt update && sudo apt install python3-pip
pip install -r requirements.txt
```

3️⃣ Run the Flask app on the EC2 instance:

```sh
python main.py
```



## ⚙️ Running the Web App

1️⃣ **Install required libraries:**

```sh
pip install -r requirements.txt
```

2️⃣ **Start the Flask app:**

```sh
python main.py
```

3️⃣ **Open in your browser:**

```
http://localhost:8000
```

## 📊 Model Training

📌 Our model was trained using real flight pricing data.
📌 It can estimate fares for flights even if no price is provided.
📌 **Key model improvements:**
✔️ Encoding airline names and travel class for better predictions
✔️ Grouping departure and arrival times into meaningful categories
✔️ Handling missing values and removing unnecessary data
✔️ Calculating flight durations for better price estimation

## 💡 Future Improvements

🔹 Improve model accuracy with deep learning techniques.
🔹 Add more data sources for better predictions.
🔹 Enable real-time fare tracking for users.
🔹 Enhance the Tableau dashboard with live updates.


