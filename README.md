# DATA 205
This is my capstone project for DATA 205 for Spring 2025 at Montgomery College.

This project was done in coordination with the Montgomery County Alcohol Beverage Services (ABS), which is responsible for regulating alcohol licensing, enforcement, and education. They are the wholesale distributor of wine, beer, and spirits in Montgomery County and also have 27 retail locations.

The ABS asked us (3 interns) to help them improve their reordering algorithm to maximize profits. They wanted us to create improvements that would reduce excess restocking, which leads to products going to waste, and prevent understocking, which leads to lost revenue. We (the 3 interns) met and discussed how to divide the workload. I decided that I would focus on determining whether the sales data that they provided us could be clustered into groups to fine-tune algorithms to different trends.

# Goal

For this project, I aim to prove that the sales data of the Alcohol Beverage Services can be clustered into groups. Clustering sales data will allow the ABS to fine-tune predictive algorithms to adjust for sales variability, volatility, and trends.

# Tool and Methods

All of the code in this project was done using r. I used the dtwclust package: I used tsclust() to create the clusters and cvi() to analyse them. I used partitional delayed time warping clustering to create the clusters.

# Outcome

I was able to create good clusters using the sales data and determined that the number of clusters into which the sales data is split can be optimized, but that there are tradeoffs associated with this.

# Repository Objects

In this repository, I have attached my data cleaning and EDA code and my data analysis code, as well as the corresponding data sets. I have also attached a written report and a presentation detailing my project.

