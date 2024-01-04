# Movie-Insights


# Table of Contents

[Project Overview](#Project-Overview)

[Data Source](#Data-Source)

[Tools](#Tools)

[Data Cleaning Tasks](#Data-Cleaning-Tasks)

[Correlation Findings](#Correlation-Findings)

[Results](#Results)

[Recommendation](#Recommendation)

[Limitations](#Limitation)

[References](#References)

### Project Overview
In this project, I aim to analyze a dataset containing information about movies to identify correlations between various variables. The dataset includes details such as budget, gross earnings, ratings, and release years for a variety of movies. By leveraging statistical analysis and visualization techniques, I seek to uncover relationships and patterns within the data.

### Data Source
The data for this project is sourced from Kaggle and it is a  CSV file named 'movies.csv'. It contains information about different movies, including attributes such as budget, gross earnings, ratings, release dates, and production companies.

### Tools
The analysis is conducted using Python programming language and several libraries for data manipulation, visualization, and analysis. The key libraries employed in this project include:
- Pandas: for data manipulation and analysis
- NumPy: for numerical operations
- Seaborn and Matplotlib: for data visualization

### Data Cleaning Tasks

#### 1. Changing Data Types
   
  - Columns: Budget and Gross

  - Reasoning: Ensuring consistency and appropriate data types for numerical analysis.

#### 2. Creating a New Year Column
   
  - Column: New Year

  - Method: Extract the first four values from the 'Year Released' column.

  - Purpose: Standardizing the year format for easier temporal analysis.

#### 3. Ordering by Gross Revenue
   
  - Column: Gross Revenue

  - Method: Sorting the dataset based on the 'Gross Revenue' column.

  - Rationale: Facilitating the identification of top-performing movies and trends in revenue.

#### 4. Checking and Dropping Duplicates
   
  - Columns: All columns

  - Method: Identifying and removing duplicate entries.

  - Purpose: Ensuring data integrity and accuracy in subsequent analyses.


### Correlation Findings

1. Votes and Budget Significantly Impact Gross Earnings:
   
- Correlation: Strong positive correlation observed.
  
- Implication: Movies with higher budgets and a greater number of votes tend to generate increased gross earnings.
  
2. Company Exhibits Low Correlation:
   
- Correlation: Lower correlation observed between the production company ("company") and gross earnings.
  
- Implication: The choice of production company alone might not be a decisive factor in a movie's financial success.

### Results

1. Votes and Budget Significantly Impact Gross Earnings: The analysis reveals a strong positive correlation between both the number of votes a movie receives and its budget with the gross earnings. This suggests that movies with higher budgets tend to generate increased revenue, potentially driven by elevated production values and marketing efforts. Additionally, a higher number of votes may indicate greater audience engagement, contributing positively to a film's financial success.

2. Company Exhibits Low Correlation: Surprisingly, the analysis indicates a lower correlation between the production company ("company") and gross earnings. This implies that the choice of production company alone might not be a decisive factor in a movie's financial success. Other variables such as genre, marketing strategies, or talent involvement might play more substantial roles in influencing box office performance.

3. Implications for Filmmakers and Industry Professionals: Filmmakers are advised to prioritize budget allocation, ensuring sufficient resources for production and marketing activities, which aligns with the identified positive correlation with gross earnings. Moreover, understanding the limited impact of the production company on financial success encourages filmmakers to focus on other critical aspects such as script quality, genre selection, and audience engagement strategies.

4. Data-Driven Decision Making: These findings emphasize the importance of data-driven decision-making in the film industry. By leveraging insights into correlations, industry professionals can make informed choices regarding resource allocation, marketing efforts, and overall film production strategies to optimize financial outcomes. 

### Recommendation

- Allocate budgets based on positive correlations between budget and gross earnings.
- Ensure sufficient resources for production and marketing activities.
- Optimize audience appeal by choosing genres with strong positive correlations.
- Tailor movie production strategies to align with genre preferences and trends.
- Align release strategies with temporal trends for enhanced box office success.
- Leverage insights into trends over time to optimize release schedules.
- Empower industry professionals with data-driven guidance for maximizing cinematic impact and financial returns.

### Limitation 
- Recognize that the identified correlations offer a focused perspective rather than an exhaustive understanding of all factors influencing movie success.
- Acknowledge the dynamic nature of the film industry, and the analysis is based on historical data, potentially missing emerging trends.
- Emphasize the importance of rigorous validation processes to address data quality concerns, including completeness and accuracy of the dataset.

### References

[Stackoverflow](https://stackoverflow.com/)

[Youtube](youtube.com)

[Github](github.com)
