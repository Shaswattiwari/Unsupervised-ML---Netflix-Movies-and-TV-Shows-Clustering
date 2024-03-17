# Unsupervised-ML---Netflix-Movies-and-TV-Shows-Clustering

This Python project focuses on analyzing Netflix content to understand the types of content available in different countries and to cluster similar content based on text-based features. The project utilizes data preprocessing, data visualization, and machine learning clustering techniques.

Abstract
This project aims to gain insights into Netflix content by analyzing the types of content available in different countries and clustering similar content based on textual descriptions. Through data visualization and machine learning clustering algorithms, the project provides valuable information for understanding Netflix's content distribution and similarity.

Introduction
The project begins by loading the Netflix dataset and handling missing values. It then proceeds to analyze the types of content available in different countries using data visualization techniques. Additionally, the project investigates whether Netflix has been increasingly focusing on TV shows rather than movies in recent years. Finally, the project clusters similar content by preprocessing textual descriptions and applying machine learning clustering algorithms.

Dependencies
To run this project, ensure you have the following dependencies installed:

pandas
re
plotly
nltk
sklearn
gap-statistic
You can install these dependencies using pip:

bash
Copy code
pip install pandas re plotly nltk scikit-learn gap-stat
How to Run
Make sure you have the Netflix dataset file, "NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv," in the same directory as your Python script.
Run the Python code.
Understanding Content Distribution Among Countries
The project visualizes the distribution of Netflix content among different countries using a choropleth map. This visualization provides insights into the number of movies and TV shows available in each country.

Analyzing Netflix's Focus on TV Shows vs. Movies
The project investigates whether Netflix has been increasingly focusing on TV shows rather than movies in recent years. It presents a line plot showing the count of movies and TV shows released each year.

Clustering Similar Content
The project clusters similar content based on textual descriptions using TF-IDF vectorization and KMeans clustering. It determines the optimal number of clusters using the Gap Statistic method. Finally, it merges the clustered data with the original dataset and presents the final clustered data.

Conclusion
The Netflix Content Analysis and Clustering project offer valuable insights into Netflix's content distribution and similarity. By analyzing content availability among countries and clustering similar content based on textual features, the project provides useful information for both Netflix users and content creators.
