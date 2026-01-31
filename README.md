🍽️ Food Delivery Hackathon – Data Analysis 📊

This repository contains the solution for the Food Delivery Hackathon conducted by Innomatics Research Labs.

The project focuses on combining multiple real-world style datasets and performing exploratory data analysis to understand user behavior, order trends and business performance.

--------------------------------------------------------------------------------

🎯 Project Objective

To build a single source of truth by merging transactional, user and restaurant data and perform analytical insights on:

📈 Order trends over time

👥 User behaviour patterns

🌍 City-wise and cuisine-wise performance

⭐ Membership impact (Gold vs Regular users)

💰 Revenue distribution and seasonality

----------------------------------------------------------------------------

📂 Files in this Repository

📓 food_delivery_analysis.ipynb
Jupyter Notebook containing complete data loading, merging and analysis.

🗂️ final_food_delivery_dataset.csv
Final merged dataset created using:

orders data

users master data

restaurants master data

--------------------------------------------------------------------------------

🔗 Dataset Preparation

The final dataset was created using the following joins:

orders.user_id → users.user_id

orders.restaurant_id → restaurants.restaurant_id

Join type used: Left Join (to retain all orders).

--------------------------------------------------------------------------------

🛠️ Tools & Technologies

🐍 Python

🐼 Pandas

📓 Jupyter Notebook

🔍 Key Insights Covered

--------------------------------------------------------------------------------

📅 Monthly order and revenue trends

🧑‍💻 Customer ordering behaviour

🏙️ Performance comparison across cities and cuisines

🏆 Revenue contribution based on membership type

🍂 Seasonal revenue patterns

--------------------------------------------------------------------------------

▶️ How to Run

📥 Clone the repository.

📓 Open food_delivery_analysis.ipynb.

📂 Make sure final_food_delivery_dataset.csv is in the same folder.

▶️ Run all cells in sequence.

--------------------------------------------------------------------------------

👤 Author

Swaroop-33
