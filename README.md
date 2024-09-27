# Movie Data Analysis - Correlation of Parameters in Highest-Grossing Movies

## Overview
This project focuses on analyzing various parameters (like score, votes, budget, and gross) of the highest-grossing movies to find correlations between them. The analysis uses Python's pandas, numpy, seaborn, and matplotlib libraries to visualize the relationships between different features of the dataset.

A heatmap of the correlation matrix is plotted to visualize the strength of the relationships between the numeric features of the dataset.

## Features
- **Data Preprocessing**: The dataset is cleaned and prepared for correlation analysis.
- **Correlation Matrix**: A Pearson correlation matrix is computed to examine the relationships between parameters like score, votes, budget, and gross.
- **Heatmap Visualization**: A heatmap of the correlation matrix is created using seaborn for visualizing the relationships between different features.

## Files in the Repository
- `movies_correlation.py`: Python script to read the dataset, compute correlations, and generate visualizations.
- `movies.csv`: The dataset containing details about movies, including name, rating, genre, year, released date, score, votes, director, writer, star, country, budget, etc.

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.x
- Pandas
- Numpy
- Seaborn
- Matplotlib

You can install the necessary dependencies using the following command:
`
pip install pandas numpy seaborn matplotlib`

## How to Run the Script
Clone the repository:
`git clone https://github.com/yourusername/Movies-Data-Analysis.git
cd Movies-Data-Analysis`

Run the script:
`python movies_correlation.py`

## Results
The visualizations provides a clear understanding with numeric evidences of how different numeric features such as score, votes, budget, and gross are correlated with one another. You can use this to identify the most significant features affecting a movie's success.



