
# Data-Driven Cricket Performance Analysis

## Overview
This project focuses on analyzing cricket batting performance using a data-driven approach. The goal is to identify consistent and high-impact batting performers by examining historical player statistics such as runs, matches, batting average, half-centuries, and centuries. The analysis helps support better decision-making for team selection, player evaluation, and performance improvement.

## Objectives
- Analyze player performance using key batting metrics (runs, matches, averages, 50s, 100s)
- Identify consistent and high-performing players through statistical analysis
- Study the relationship between total runs, centuries, and batting averages
- Understand patterns in converting half-centuries into centuries
- Support data-driven decision-making for team selection and coaching strategies

## Data & Methodology
Cricket player data was collected through web scraping techniques using Selenium and BeautifulSoup. The data was cleaned, structured, and analyzed using Python libraries. Exploratory Data Analysis (EDA) was performed through univariate, bivariate, and multivariate analysis, followed by hypothesis testing to validate observed performance patterns.

## Dataset Overview
- The dataset contains batting performance statistics of cricket players
- Key variables include runs, matches played, batting average, number of 50s, and 100s
- Each record represents an individual player’s overall career or tournament performance
- Includes both consistency metrics (average, 50s) and high-impact metrics (100s)
- Suitable for statistical analysis and performance comparison

## Key Insights
- Players with higher total runs generally score more centuries, indicating consistency and impact
- Batting average is relatively independent of the number of matches played
- Strong positive correlation exists between half-centuries and centuries
- Most players fall into medium and high consistency categories
- Only a small percentage of players show low performance, indicating a strong dataset overall

## Analysis Performed
- **Univariate Analysis**: Distribution of runs, averages, and scoring patterns among top players
- **Bivariate Analysis**: Relationship between runs vs centuries and runs vs batting average
- **Multivariate Analysis**: Correlation analysis among runs, matches, averages, 50s, and 100s
- **Hypothesis Testing**: Validation of performance consistency and scoring behavior

## Applications & Recommendations
- Helps selectors identify reliable and high-impact batting performers
- Supports objective, data-driven team selection decisions
- Assists coaches in designing focused training programs
- Highlights the need to improve conversion from half-centuries to centuries
- Enables performance monitoring and long-term player evaluation

## Tools Used
- Python  
- Selenium  
- BeautifulSoup  
- Pandas  
- NumPy  
- Matplotlib  

## Conclusion
This project demonstrates how cricket performance data can be effectively used to evaluate consistency and match-winning ability. The analysis highlights strong relationships between runs, averages, and milestone scores, emphasizing the importance of both consistency and impact. Overall, the project provides actionable insights for cricket analytics, team strategy, and performance improvement.

