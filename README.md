# Zomato_EDA
🍽️ Zomato Restaurant Data Analysis
A comprehensive exploratory data analysis (EDA) of Zomato restaurant data using Python. This project provides deep insights into restaurant ratings, pricing, online ordering patterns, and customer preferences through statistical analysis and rich visualizations.
📊 Project Overview
This project analyzes restaurant data from Zomato to uncover meaningful patterns and insights about:
•	Restaurant ratings and customer satisfaction
•	Pricing strategies across different restaurant types
•	Online ordering and table booking preferences
•	Regional dining trends and preferences
•	Statistical relationships between various restaurant features
🚀 Features
•	Comprehensive Data Cleaning: Handles missing values, rating formats, and cost standardization
•	Rich Visualizations: 15+ interactive plots including histograms, scatter plots, heatmaps, and box plots
•	Statistical Analysis: T-tests for significance testing and correlation analysis
•	Advanced Insights: Restaurant ranking, cost analysis, and preference patterns
•	Google Colab Ready: Optimized for cloud-based analysis with easy file loading options

Install required packages
pip install pandas numpy matplotlib seaborn scipy
📂 Dataset
The analysis is done on a CSV file with the following columns:
•	name: Restaurant name
•	rate: Restaurant rating (handles formats like "4.1/5", "NEW", "-")
•	approx_cost(for two people): Cost for two people
•	votes: Number of votes/reviews
•	online_order: Online ordering availability (Yes/No)
•	book_table: Table booking availability (Yes/No)
•	listed_in(type): Restaurant type/category
Sample Data Format
name,rate,votes,approx_cost(for two people),online_order,book_table,listed_in(type)
Jalsa,4.1/5,775,"800",Yes,Yes,Casual Dining
Spice Elephant,4.1/5,787,"800",No,No,Casual Dining

📈 Analysis Sections
1. Data Quality Assessment
•	Missing value analysis
•	Duplicate detection
•	Data type validation
•	Unique value inspection
2. Data Cleaning & Preprocessing
•	Rating standardization (handles "4.1/5" → 4.1)
•	Cost normalization (removes commas, handles currency)
•	Column renaming for easier analysis
3. Descriptive Statistics
•	Summary statistics for numerical columns
•	Distribution analysis for categorical variables
•	Central tendency and spread measures
4. Comprehensive Visualizations
•	Rating Distribution: Histogram of restaurant ratings
•	Cost Analysis: Distribution of costs for two people
•	Voting Patterns: Customer engagement analysis
•	Service Availability: Online ordering and table booking trends
•	Restaurant Categories: Type-wise distribution and analysis
•	Correlation Matrix: Relationship between numerical variables
•	Top Performers: Highest-rated restaurants
5. Statistical Testing
•	T-tests for comparing ratings across service types
•	Significance testing for online vs offline restaurants
•	Correlation analysis between price, rating, and popularity
6. Advanced Insights
•	Restaurant ranking by various metrics
•	Cost-effectiveness analysis
•	Regional preference patterns
•	Service availability impact on ratings
📊 Key Insights Discovered
•	🏆 Rating Patterns: Most restaurants fall in the 3.5-4.5 rating range
•	💰 Pricing Strategy: Clear correlation between restaurant type and pricing
•	📱 Digital Adoption: Significant percentage of restaurants offer online ordering
•	🎯 Customer Preference: Higher-rated restaurants tend to have more votes
•	📈 Market Trends: Casual dining dominates the restaurant landscape
🎨 Visualization Gallery
The analysis produces 15+ professional visualizations including:
•	Distribution plots for ratings, costs, and votes
•	Comparative analysis charts
•	Correlation heatmaps
•	Restaurant ranking charts
•	Service availability breakdowns


🏷️ Tags
data-analysis python pandas matplotlib seaborn eda zomato restaurant-analysis data-science visualization statistics jupyter-notebook google-colab
________________________________________
⭐ Star this repository if you found it helpful! ⭐

