# Data Analysis Project: AMCAT Data Exploration

## Project Overview
This project focuses on analyzing the Aspiring Minds Employment Outcome 2015 (AMEO) dataset, which contains employment outcomes of engineering graduates. The main goal of the project is to explore the relationship between various factors such as education, demographics, personality traits, and specialization, and their impact on salary. The analysis covers a range of data exploration techniques, including univariate and bivariate analysis, and draws insights that could guide career decisions.

### Objectives
- **Analyze Salary Influences**: Identify and analyze the various factors that significantly influence salary levels among engineering graduates.
- **Explore Educational Impact**: Investigate how educational qualifications, such as GPA and specialization, affect employability and salary.
- **Understand Demographic Factors**: Examine the role of demographic factors (age, gender, location) in shaping career outcomes for graduates.

## Data Information
The dataset contains around 4000 data points and includes approximately 40 independent variables. The features are a mix of continuous and categorical variables. Key features include:
- **Dependent Variables**: Salary, Job Title, Job Location
- **Independent Variables**: Cognitive skills, technical skills, personality traits, demographic information, education details, etc.
- **Unique Identifier**: Each row corresponds to a unique candidate.

## Project Structure
The project follows a structured approach, divided into the following sections:
1. **Introduction**: 
   - This section provides a detailed overview of the project, outlining its goals, objectives, and significance.
   - It sets the context for the analysis by discussing the importance of understanding salary determinants in the engineering job market.
   - We introduce the AME dataset and the various factors it encompasses, which will be the focus of our exploration.
2. **Data Loading and Overview**: 
   - In this part, we will load the dataset using appropriate libraries, such as Pandas.
   - An initial overview of the data will be presented to familiarize the reader with its structure, dimensions, and the types of features included.
   - By examining the first few rows of the dataset, we can gain insights into its contents and prepare for further analysis.
3. **Sanity Check of the Data**: Checking and fixing data types, handling missing values, and ensuring the data is clean for analysis.
4. **Univariate Numerical Analysis**: Conducting numerical analysis for each independent numerical feature, including detecting and removing outliers using the boxplot, IQR, and Z-score method.
5. **Univariate Categorical Analysis**: Analyzing categorical variables with count plots to understand the distribution of job roles, job locations, gender, education boards, etc.
6. **Bivariate Analysis**:
   - **Numerical vs Numerical**: Examining relationships between salary and other numerical variables using pair plots and heatmaps.
   - **Numerical vs Categorical**: Analyzing salary across categorical variables such as college tier, percentage scores, specialization, degree, and gender using bar plots and box plots.
   - **Categorical vs Categorical**: Exploring relationships between specializations, roles, and degrees.
7. **Research Questions**: Key research questions addressed through data analysis.
8. **Conclusions**: Summary of the key insights drawn from the data analysis.
9. **Bonus Insights**: Additional observations and insights discovered during the analysis.
## Requirements
This project was developed using Python, and the following libraries are required to run the code:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

## How to Run
1.Install the necessary libraries:
  ```bash
   pip install pandas numpy seaborn matplotlib plotly scipy
   ```
2.Open the Jupyter Notebook file (.ipynb) and run the cells in order to reproduce the analysis.
