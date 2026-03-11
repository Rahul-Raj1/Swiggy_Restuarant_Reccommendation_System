Swiggy Restaurant Recommendation System
📌 Project Overview

This project builds a Restaurant Recommendation System inspired by Swiggy using Python, Machine Learning, and Streamlit.
The system recommends restaurants based on user preferences such as city, cuisine, rating, and cost.

The goal of the project is to demonstrate how data preprocessing, feature encoding, and clustering algorithms can be used to generate meaningful restaurant recommendations and display them through an interactive dashboard.

🎯 Objectives

Build a restaurant recommendation system using restaurant dataset.

Perform data cleaning and preprocessing.

Apply One-Hot Encoding on categorical features.

Use K-Means clustering for grouping similar restaurants.

Develop an interactive dashboard using Streamlit.

📊 Dataset Description

The dataset contains restaurant information with the following columns:

Column	Description
name	Restaurant name
city	City where restaurant is located
cuisine	Type of cuisine served
rating	Restaurant rating
rating_count	Number of ratings
cost	Average cost for two
⚙️ Technologies Used

Python

Pandas

Scikit-learn

Streamlit

K-Means Clustering

🔄 Project Workflow

1️⃣ Data Collection
2️⃣ Data Cleaning
3️⃣ Data Preprocessing
4️⃣ One-Hot Encoding
5️⃣ K-Means Clustering
6️⃣ Recommendation Generation
7️⃣ Streamlit Dashboard Visualization

🧠 Recommendation Method

The system uses K-Means clustering to group restaurants with similar features such as:

City

Cuisine

Cost

Rating

When the user selects preferences, the system finds restaurants belonging to the most relevant cluster and recommends them.

💻 Streamlit Dashboard Features

The interactive dashboard allows users to:

Select City

Select Cuisine

Filter by Minimum Rating

Filter by Maximum Cost

Select Number of Recommendations

After clicking Recommend Restaurants, the dashboard displays:

Restaurant Name

Rating

Rating Count

Cost

It also shows insights such as:

Total restaurants recommended

Average rating

Average cost

📂 Project Structure
Restaurant-Recommendation-System
│
├── cleaned_swiggy.csv
├── encoded_data.csv
├── encoder.pkl
├── app.py
├── README.md
└── requirements.txt
