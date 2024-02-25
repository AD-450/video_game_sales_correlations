# Video Game Sales Analysis

## Project Overview
This project involves a comprehensive analysis of video game sales data to uncover insights into regional sales trends and their impact on global sales figures. By examining sales across North America, Europe, Japan, and other regions, the project aims to identify key patterns, including which markets have the strongest influence on global sales success.

## Data Description

The dataset includes video game sales data, featuring the following columns:

- `Rank` - Ranking of overall sales
- `Name` - The name of the video game
- `Platform` - Platform of the game (e.g., PC, PS4, etc.)
- `Year` - Year of the game's release
- `Genre` - Genre of the game
- `Publisher` - Publisher of the game
- `NA_Sales` - Sales in North America (in millions)
- `EU_Sales` - Sales in Europe (in millions)
- `JP_Sales` - Sales in Japan (in millions)
- `Other_Sales` - Sales in other regions (in millions)
- `Global_Sales` - Total worldwide sales (in millions)

## Analysis Workflow

- `Data Loading:` Importing the dataset into a Python environment using pandas.
- `Data Cleaning:` Addressing missing, incorrect, or irrelevant data to ensure the dataset is ready for analysis.
- `Correlation Analysis:` Calculating the correlation coefficient matrix for sales columns to explore the relationships between regional sales figures and global sales.
- `Insight Generation:` Identifying and interpreting the strongest and weakest correlation pairs to gain insights into market dynamics.

## Key Findings

North America sales are highly predictive of global sales trends, suggesting its market's significant influence on the video game industry.
The Japanese market shows unique preferences, as indicated by the weaker correlation between Japan sales and other regions, highlighting the importance of tailoring strategies for this distinct market.

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization

## How to Run the Project
Clone this repository to your local machine.
```
https://github.com/AD-450/video_game_sales_correlations.git
```
Ensure you have Python and the necessary libraries installed.
Run the Jupyter Notebook to explore the analysis and findings.
