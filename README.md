# RESTAURANT-RECOMMENDATION
1)Project Overview : 
This project implements a content-based restaurant recommendation system that suggests restaurants to users based on their preferences such as cuisine type, location, price range, and minimum rating.
The system uses restaurant metadata (e.g., city, cuisines, average cost, rating) and compares it against user input using similarity metrics to return relevant recommendations.

2)Dataset Summary : 
The dataset contains the following attributes:
Restaurant name
City and locality
Cuisines offered
Average cost for two
Price range
Aggregate rating
Latitude and longitude coordinates
Online delivery and table booking availability

3)Recommendation Approach : 
The system uses content-based filtering based on user-defined preferences.
User Inputs:
Preferred cuisine (e.g., "Italian")
City (e.g., "Delhi")
Maximum acceptable cost (e.g., 1500)
Minimum acceptable rating (e.g., 3.5)

4)Recommendation Logic : 
Filter restaurants that meet the user’s basic preferences.
Convert restaurant features into numeric format using one-hot encoding.
Compute a user profile vector and calculate cosine similarity with the dataset.
Recommend the top N restaurants with the highest similarity scores.

5)Technologies Used : 
Python
Pandas (data manipulation)
Scikit-learn (similarity computation and preprocessing)
Folium (optional: interactive map visualization)
