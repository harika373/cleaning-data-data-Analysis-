# cleaning-data-data-Analysis-:

🧹 Data Cleaning Project

This project demonstrates data cleaning techniques on two real-world datasets:

New York City Airbnb Open Data (AB_NYC_2019.csv)
Source: Kaggle – NYC Airbnb

YouTube Trending Video Statistics (USvideos.csv + category JSON)
Source: Kaggle – YouTube Trending Dataset

The goal is to prepare these datasets for reliable analysis by applying five key data cleaning rules.


🔑 Key Concepts & Challenges

Data Integrity

Ensure values are valid and consistent (e.g., valid coordinates, positive prices, non-negative views).

Missing Data Handling

Replace missing values with appropriate substitutes (e.g., reviews_per_month = 0, tags = "No Tags").

Duplicate Removal

Remove redundant records based on unique identifiers (e.g., id in Airbnb, video_id + trending_date in YouTube).

Standardization

Convert inconsistent formats (e.g., price strings → numeric, room_type capitalization, category_id mapping).

Outlier Detection

Identify and remove anomalies using IQR (Airbnb prices) or Z-score (YouTube views/likes/dislikes).

