# EDA-Using-Python

# EDA-Using-Python

## Overview
This project demonstrates Exploratory Data Analysis (EDA) and visualization techniques using Python. The dataset contains family-related details, such as roles, countries, salaries, and expenses. The goal is to clean, explore, and visualize the data to uncover meaningful patterns and insights.

## Features
- **Data Cleaning**:
  - Removed duplicate records and ensured no missing values.
  - Converted numeric columns like `Salary`, `Food_Expenses`, and `Rent_Expenses` into appropriate formats.
- **Data Exploration**:
  - Examined the structure and summary statistics of the dataset.
  - Filtered and sorted data to identify specific trends, such as high food expenses.
- **Descriptive Statistics**:
  - Calculated averages, standard deviations, and medians for numerical columns.
  - Analyzed categorical variables like `Current_Country` and `WhoAreThey`.
- **Visualizations**:
  - Visualized data relationships and distributions using Matplotlib, Seaborn, and Plotly.

## Visualizations
### 1. **Salary Distribution**
- A histogram showing the distribution of salaries across individuals. 
- Most salaries are clustered between $60,000 and $90,000, with fewer individuals at the extreme ends.

### 2. **Average Rent Expenses by Country**
- A bar chart comparing rent expenses between Canada and Nepal.
- Highlights significantly higher rent expenses in Canada, reflecting regional cost-of-living differences.

### 3. **Scatter Plot: Salary vs Rent Expenses**
- A scatter plot showing the relationship between salaries and rent expenses.
- Demonstrates that higher salaries often correlate with higher rent expenses, particularly in Canada.

### 4. **Box Plot: Food Expenses by Family Role**
- A box plot visualizing the variability in food expenses across family roles.
- Roles like "Me" and "Father" have consistent expenses, while "Sister" shows greater variability.

### 5. **Treemap: Salary and Rent Expenses by Role and Country**
- A treemap representing salary and rent expenses hierarchically by roles and countries.
- Block sizes represent salaries, while colors indicate rent expenses, offering an intuitive overview.

## Technologies Used
- **Python**: Core language for the project.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib**: Static visualizations.
- **Seaborn**: Advanced statistical plots.
- **Plotly**: Interactive and hierarchical visualizations.
