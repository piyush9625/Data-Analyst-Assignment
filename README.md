# Data Analyst Intern Assignment

## Overview
This project involves analyzing datasets related to user behavior, cooking preferences, and order trends. The goal is to derive insights, visualize key findings, and provide actionable business recommendations.

## Datasets
The analysis is based on three datasets:
1. **UserDetails**: Contains user demographics and behavior attributes.
2. **CookingSessions** (if available): Includes details about users' cooking activities.
3. **OrderDetails** (if available): Records information about user orders.

## Objectives
- Clean and merge datasets.
- Analyze the relationship between cooking sessions and user orders.
- Identify popular dishes.
- Explore demographic factors that influence user behavior.
- Visualize findings and provide business recommendations.

## Methodology
1. **Data Cleaning**:
   - Handled missing or inconsistent values.
   - Standardized column names and formats for merging.

2. **Data Integration**:
   - Merged datasets using common keys (e.g., `UserID`).

3. **Analysis**:
   - Investigated meal preferences (e.g., Dinner, Lunch, Breakfast).
   - Explored age and location trends related to meal choices.
   - Identified order trends and popular dishes.

4. **Visualization**:
   - Created bar charts, pie charts, and demographic breakdowns to showcase insights.

5. **Findings and Recommendations**:
   - Summarized insights from data trends.
   - Proposed actionable recommendations based on analysis.

## Key Insights
- **Meal Preferences**:
  - Dinner is the most popular meal, followed by Lunch and Breakfast.
  - Younger users prefer Dinner, while older users tend to favor Breakfast.

- **Demographics**:
  - Regional preferences show Dinner as dominant in most locations, while Lunch and Breakfast are more niche.

- **Order Trends**:
  - Dinner accounts for the highest total orders, making it a key focus for marketing efforts.

## Tools Used
- **Python**:
  - Libraries: Pandas, Matplotlib, Seaborn for data manipulation and visualization.
- **GitHub**:
  - For version control and project organization.

## Repository Structure
```
project-folder/
├── data/
│   ├── UserDetails.csv
│   ├── CookingSessions.csv (if available)
│   ├── OrderDetails.csv (if available)
├── notebooks/
│   ├── data_analysis.ipynb
├── visualizations/
│   ├── meal_popularity.png
│   ├── order_trends_piechart.png
├── README.md
```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook in `notebooks/` to reproduce the analysis and visualizations.

## Business Recommendations
- Focus marketing efforts on Dinner, the most popular meal.
- Create targeted campaigns for different age groups:
  - Younger users: Highlight Dinner specials.
  - Older users: Promote Breakfast options.
- Explore regional preferences to offer localized meal options.

---

For more details, refer to the analysis notebook in the `notebooks/` directory.
