Zomato Data Analysis Project
Overview
This project provides a comprehensive analysis of Zomato restaurant data to uncover insights into dining trends, customer preferences, and the factors influencing restaurant ratings. Using Python's data science libraries, we explore the relationship between various features such as online ordering, cost, and restaurant types.

Dataset Description
The dataset contains information on 148 restaurants with the following columns:

name: Name of the restaurant.

online_order: Indicates if online ordering is available (Yes/No).

book_table: Indicates if table booking is available (Yes/No).

rate: The rating of the restaurant (e.g., 4.1/5).

votes: The total number of ratings/votes the restaurant received.

approx_cost(for two people): The average cost for a meal for two.

listed_in(type): The category of the restaurant (e.g., Buffet, Cafes, Dining).

Key Objectives
Clean and preprocess the restaurant data for analysis.

Visualize the distribution of restaurant types and ratings.

Analyze the impact of online ordering on customer ratings.

Determine the preferred price range for couples.

Identify which restaurant types receive the highest engagement (votes).

Technologies Used
Python: Core programming language.

Pandas: For data cleaning and manipulation.

NumPy: For numerical computations.

Matplotlib & Seaborn: For data visualization.

Analysis & Visualizations
Data Cleaning: Transformed the rate column by removing the "/5" suffix and converting it to a numerical format for calculation.

Restaurant Type Distribution: Used count plots to identify that the majority of restaurants belong to the Dining category.

Rating Analysis: Visualized the distribution of ratings, finding that most restaurants score between 3.5 and 4.0.

Online Order vs. Rating: A box plot analysis revealed that online orders generally receive higher ratings compared to offline orders.

Cost for Two: Analyzed the "approx_cost" and found that a significant number of customers/couples prefer restaurants with a cost around 300 rupees.

Heatmap Correlation: Created a heatmap to visualize the relationship between the dining type and the availability of online ordering.

Conclusion
Dining is the most popular restaurant type and also receives the maximum number of votes.

There is a positive correlation between online ordering availability and higher customer ratings.

Budget-friendly dining (approx. 300 rupees for two) is the most preferred price point in the dataset.

How to Run
Ensure you have Python installed.

Install the required libraries:

Bash
pip install pandas numpy matplotlib seaborn
Place Zomato data .csv in the same directory as the script.

Run the Jupyter Notebook or Python script to generate the analysis.
