# Labor Market Dynamics in the United States

## Abstract
This project aims to thoroughly examine patterns in employment and economic stability by analyzing demographic and gender differences, educational factors, wage trends, and the influence of economic events over an extended period. By leveraging diverse datasets, we provide valuable visualizations that can help stakeholders in education, business, and policy make informed, data-driven decisions.

## Introduction
Understanding employment trends and their relationships with demographic factors, education, and economic events is crucial in today's global economy. This project offers a comprehensive exploration of employment dynamics with a focus on demographic differentials, educational influences, wage trends, and the impact of economic events. Visualization plays a key role in translating complex data into meaningful insights.

## Datasets
- **State-wise average wages of different age groups**: Average annual income in different states categorized by age groups.
- **State-wise average wages of different demographics**: Average weekly income in different states categorized by demographics.
- **State-wise average wages of genders**: Average weekly income in different states categorized by gender.
- **Median wages based on Educational Attainment in the US**: Average weekly income categorized by different educational attainments.
- **Average wages of genders and different demographics of the US (1973-2022)**: Average hourly wages categorized by demographics and genders from 1973 to 2022.
- **Average wages based on Educational Attainment in the US (1973-2022)**: Average hourly wages categorized by educational attainments from 1973 to 2022.

## Visualization Design
The interactive visualization explores labor market dynamics in the USA, providing insights into demographic, age group, gender, and education-related data. The design includes:
- **Heat Map**: Choropleth map shading states based on selected categories.
- **Spider Charts (Radviz)**: Visualizes data for age groups, demographics, and education levels.
- **Stacked Area Graph**: Represents temporal evolution of wage distribution.
- **Stacked Bar Chart**: Highlights gender-related wage distribution over the years.

## Implementation
### Data Pre-Processing
- **Data Cleaning**: Standardizing data, handling missing values, and dealing with outliers.
- **Data Normalization**: Ensuring consistent scales for visualization.

### Data Exploration and Insights
- **Demographic and Regional Trends**: Choropleth maps to explore wage disparities visually.
- **Temporal Wage Trends**: Stacked area charts for gender-based wage trends over the years.
- **Multivariate Analysis**: Spider charts for comparing the impact of age, demographics, and education on wages.
- **Education and Income Distribution**: Stacked bar chart illustrating wage distribution based on education levels.

### User Interaction and Customization
- Interactive dropdowns for customizing exploration.
- Dynamic updates based on user selections.

## Results
### Summary of Trends (1973-2022)
- **Gender**: Men's median income shows more fluctuations while women's median income has a steadier increase.
- **Race**: White median income is more stable, black median income shows variability, and Hispanic median income demonstrates an overall increasing trend.
- **Education**: Positive income trajectories across education levels, with advanced degrees showing steady growth.

### State-Level Overview (2023)
- **Age Groups**: Highest median incomes in Washington, D.C., lowest in Mississippi.
- **Demographics**: Highest earnings for Asian-Pacific Islanders, lowest for Hispanic/Latino.
- **Gender**: Highest earnings for males in Massachusetts, for females in the District of Columbia.
- **Education**: Highest wages in New York, lowest in Mississippi.

## Conclusion
The data underscores regional education gaps, the significance of advanced degrees, persistent challenges in Mississippi, age-related income dynamics, racial demographic nuances, and gender-specific economic landscapes. These insights can guide targeted interventions for sustainable economic growth.

## How to Use
1. **Install dependencies**: Ensure you have the necessary libraries installed.
2. **Run the visualization**: Start a local server and run the `index.js` file.
3. **Interact with the dashboard**: Use dropdowns to customize the data view and explore labor market dynamics.
