# Competitive MOBA Gameplay Analysis

## Motivation

This project focuses on analyzing personal gameplay data from a competitive MOBA game to better understand performance trends, playstyle patterns, and long-term improvement.

By examining match history and character usage data, the goal is to gain actionable insights into how gameplay behavior evolves over time and which factors contribute most to performance improvement.

The analysis aims to answer questions such as:
- Which characters are played most frequently?
- How performance metrics change over time
- How rank progression evolves across different seasons
- Which characters yield the most consistent results

---

## Tools & Technologies

The following tools and libraries were used for data collection, processing, and analysis:

- **Python** – Primary language for data scraping, cleaning, and analysis  
- **Selenium** – Automated data extraction from web-based match history sources  
- **Pandas** – Data cleaning, transformation, and aggregation  
- **Matplotlib & Seaborn** – Data visualization and exploratory analysis  

---

## Data Source

All data used in this project was collected from a public match history and statistics platform for competitive MOBA games.

The dataset includes:
- Match-level data (dates, performance metrics, rankings)
- Character-level data (games played, win rates, KDA-style metrics)

Data was collected using automated web scraping scripts and processed locally.

---

## Data Processing

### Match Data
- **Rank Normalization**: Text-based ranks (e.g., tier + division) were converted into numerical values for quantitative analysis
- **Data Cleaning**: Matches with missing or invalid values were removed to ensure consistency

### Character Data
- **Aggregation Across Seasons**: Statistics for the same character were combined across multiple seasons
- **Filtering**: Characters with insufficient data or zero activity were excluded from analysis

---

## Data Visualizations

The following visual analyses were performed:

- **Seasonal Rank Progression**  
  Bar charts showing average rank achieved per season

- **Playtime Distribution**  
  Estimated total playtime per season based on average match duration

- **Character Usage Analysis**  
  - Top most-played characters by total games  
  - Comparison of performance metrics such as KDA-style ratios  

- **Performance Trends Over Time**  
  Line charts showing rank or performance changes across consecutive matches

---

## Data Analysis

Key analytical insights include:

- **Rank Progression Analysis**  
  Evaluation of long-term improvement and seasonal performance trends

- **Character Effectiveness**  
  Identification of characters with higher win rates and more stable performance

- **Consistency Across Seasons**  
  Comparison of performance metrics for the same characters over different time periods

- **Statistical Comparisons**  
  Basic hypothesis testing to identify significant differences between characters or seasons

---

## Conclusion

This project demonstrates how personal gameplay data from competitive multiplayer games can be transformed into meaningful insights through data analysis.

Key outcomes include:
- Identification of the most effective and frequently used characters
- Clear visualization of performance improvement over time
- Better understanding of playstyle consistency and variability across seasons

Overall, the project highlights the value of data-driven self-analysis in competitive gaming environments.
