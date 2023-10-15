# Data Science Project: U.S. Home Prices Analysis

## Overview
This data science project aims to analyze key factors that influence U.S. home prices nationally over the last 20 years. The S&P Case-Shiller Home Price Index is used as a proxy for home prices.

## Project Structure
The project is organized into the following sections:

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Model Development
5. Model Evaluation
6. Results and Insights
7. Conclusion

## Data Collection
### Data Sources
- S&P Case-Shiller Home Price Index.
- Additional data sources for factors influencing home prices were collected.

## Data Preprocessing
- Cleaning, formatting data and merging datasets were performed in this phase.
- Specific data preprocessing steps include:
1. **Data Collection**:
   - Collect data from various sources, including the S&P Case-Shiller Home Price Index and additional datasets for influencing factors.

2. **Data Integration**:
   - Combine and merge data from multiple sources if needed. Ensure consistency in data formats.

3. **Data Transformation**:
   - Convert data types to the appropriate format, i.e., changing date formats.
   - Apply feature scaling, normalization, or standardization required for the modeling algorithm.

4. **Handling Date and Time Data**:
    - Extract relevant information from date and time data, such as day of the week, month, year, etc., for modeling purposes.

5. **Data Splitting and Cross-Validation**:
    - Split the dataset into training, validation, and testing sets, and consider cross-validation strategies to evaluate model performance.

## Exploratory Data Analysis (EDA)
- EDA was conducted to understand the distribution of variables, identify outliers, and explore correlations.
- Key EDA findings include 

## Model Development
- An Artificial Neural Network (ANN) was built to model the relationships between key factors and home prices.
- The architecture of the ANN is described as follows:
1. 2 Hidder layers having relu activation function and 32 neurons each.
2. Output layer having 1 neuron.
3. Loss function used is Mean Squared Error (MSE).

## Model Evaluation
- Model performance was evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE).
- The model demonstrated strong predictive power with a very low MSE and very low MAE.
  
## Conclusion

1. **Influential Factors**: The analysis identified several key factors that have a substantial impact on U.S. home prices on a national scale. These factors include economic indicators, interest rates, supply and demand dynamics, government policies, and location-related variables.

2. **Data Preprocessing**: The project involved rigorous data preprocessing, encompassing data cleaning and feature engineering. These steps were crucial in ensuring the data's quality and suitability for analysis.

3. **Deep Learning Model**: An Artificial Neural Network (ANN) was employed to model the complex relationships between the identified factors and home prices. The ANN exhibited strong predictive power, with low loss and high R-squared values, indicating its effectiveness.

4. **Data Interpretation**: The ANN model provided valuable insights into the relative importance of different factors in influencing home prices. This enhanced our understanding of the dynamics within the U.S. housing market.

5. **Data Visualization**: Data visualization was utilized to convey trends in variables effectively. This visual representation aided in making the analysis more accessible and interpretable.

6. **Predictive Power**: The ANN's capability to predict home prices underscores the informativeness of the selected factors and its capacity to capture underlying data patterns.

7. **Implications**: The project's findings have significant implications for real estate professionals, policymakers, and investors. It equips them with valuable insights to make informed decisions regarding home purchases and investments.

8. **Further Research**: The results and modeling approach serve as a strong foundation for future research and analysis within the real estate and economic domains. It opens avenues for more in-depth investigations. An RNN can be used to model the data along with ANN to produce more better results.

9. **Documentation and Reproducibility**: The project is thoughtfully documented with a README file, ensuring that the methodology and results are accessible and reproducible for reference and potential collaboration.

10. **Limitations**: The project acknowledges potential limitations, such as data constraints and model assumptions. It also highlights areas for future research and improvement, maintaining transparency and integrity.

These takeaways encapsulate the significance of the project's findings and the depth of insights it provides into the factors driving U.S. home prices. The meticulous data preprocessing, modeling, and interpretation collectively contribute to a comprehensive analysis of the U.S. housing market.


## Requirements
- Python 3.x
- Data science libraries NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn, TensorFlow.
- Jupyter Notebook (for code execution and documentation)

## Acknowledgments
- [Case Shiller Home Price Index](https://fred.stlouisfed.org/series/CSUSHPISA).
- [More Data sources](https://www.macrotrends.net/).
