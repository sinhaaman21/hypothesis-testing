# Bike Sharing Data Analysis and Hypothesis Testing

This project performs a comprehensive analysis of a bike-sharing dataset to explore and identify significant relationships and differences in bike rental patterns. The analysis includes data preprocessing, exploratory data analysis (EDA), and hypothesis testing to draw meaningful inferences and recommendations.

## Project Overview

The primary goals of this project are:

1. **Exploratory Data Analysis (EDA)**:
   - Examine the dataset structure, characteristics, and statistical summary.
   - Identify and impute missing values.
   - Identify and remove duplicate records.
   - Analyze the distribution of numerical and categorical variables.
   - Check for and handle outliers.

2. **Hypothesis Testing**:
   - Establish relationships between dependent and independent variables.
   - Test if there is a significant difference in the number of bike rides between weekdays and weekends.
   - Test if the demand for bicycles on rent is the same across different weather conditions.
   - Test if the demand for bicycles on rent is the same across different seasons.
   - Test if weather conditions are significantly different during different seasons.

## Data

The dataset used in this analysis is `bike_sharing.csv`. Ensure that this file is available in the same directory as the notebook.

## Dependencies

The following libraries are required to run the analysis:
- `pandas`
- `seaborn`
- `numpy`
- `matplotlib`
- `scipy`

You can install these libraries using the following command:
```bash
pip install pandas seaborn numpy matplotlib scipy
```

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. **Load and Examine the Dataset**:
    - Load the dataset using `pandas`.
    - Display the first few records, dataset information, and statistical summary.

3. **Data Cleaning**:
    - Identify and handle missing values.
    - Check for and remove duplicate records.

4. **Exploratory Data Analysis (EDA)**:
    - Analyze the distribution of numerical and categorical variables.
    - Identify and handle outliers using the Interquartile Range (IQR) method.

5. **Hypothesis Testing**:
    - Perform 2-sample independent t-test to check for differences in bike rides between weekdays and weekends.
    - Perform one-way ANOVA tests to check for differences in bike rental demand across different weather conditions and seasons.
    - Perform Chi-square test of independence to check if weather conditions differ significantly across different seasons.

## Code

The core steps of the analysis are implemented in the Jupyter Notebook `Yulu - Hypothesis Testing.ipynb`. You can open this notebook using Jupyter Notebook or Google Colab to explore the code and execute the analysis.

## Conclusions and Recommendations

1. **Weekdays vs Weekends**:
    - There is a significant difference in the number of bike rides between weekdays and weekends.

2. **Weather Conditions**:
    - The demand for bicycles on rent varies significantly across different weather conditions.

3. **Seasons**:
    - The demand for bicycles on rent varies significantly across different seasons.

4. **Weather Conditions by Season**:
    - Weather conditions are significantly different during different seasons.

### Recommendations

1. **Resource Allocation**:
   - Adjust resource allocation for bike-related services based on the observed differences between weekdays and weekends.

2. **Marketing Strategies**:
   - Tailor marketing strategies or promotions to account for variations in demand between different weather conditions and seasons.

3. **Seasonal Business Adjustments**:
   - Make seasonal adjustments to business strategies, marketing efforts, and resource allocation.

4. **Customer Engagement**:
   - Leverage the understanding of weather-season associations to enhance customer engagement.

5. **Further Analysis**:
   - Explore specific factors contributing to significant differences for targeted interventions.

## Author

Aman Sinha - sinha.amansinha@gmail.com
