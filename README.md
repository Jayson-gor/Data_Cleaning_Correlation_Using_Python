
# Data Cleaning and Correlation Analysis
This Python project aims to clean and analyze a dataset using pandas and seaborn libraries to perform correlation analysis. The dataset used for this project is "movies.csv".

## Getting Started
To run this project, ensure you have the required libraries installed, such as pandas, seaborn, numpy, and matplotlib.

## Loading the Data
use  this line of code to load data depending on the file location
df = pd.read_csv(r"C:\Users\gorja\Downloads\python\movies.csv")

## Data Cleaning
Checking for missing data and data types present in the columns.
Changing the data types for the 'budget', 'gross', and 'votes' columns.
Creating a new column 'year_correct' by extracting the year from the 'released' column.
Sorting the 'gross' column in ascending values.
Dropping any duplicate rows.

## Data Visualization
Scatter plot of 'budget' vs 'gross' earnings.
Scatter plot using seaborn library.
Heatmap of the correlation matrix.
Heatmap of the correlation matrix for all columns.

## Numerizing Columns
Converting object type columns to numeric using categorical codes.

## Correlation Analysis
Calculating the correlation matrix and identifying high correlated pairs.

## Conclusion
Based on the correlation analysis, it was found that 'votes' and 'budget' have the highest correlation to 'gross' earnings. The project also provides insights into other correlations within the dataset.

Feel free to explore and modify the code according to your requirements.

## Note: Make sure to have the necessary dependencies installed and the dataset path updated before running the code.
