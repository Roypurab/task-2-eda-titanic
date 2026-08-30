# Titanic Dataset - Exploratory Data Analysis

## Objective

To perform Exploratory Data Analysis (EDA) on the Titanic dataset
and identify important patterns, relationships, distributions,
and potential outliers.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab

## Dataset

The Titanic dataset contains passenger information such as:

- PassengerId
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Survived

## Key EDA Findings

The Titanic dataset contains both numerical and categorical features
that can be analyzed using descriptive statistics and visualizations.

- Fare is positively skewed, with a small number of passengers paying
  significantly higher fares.
- The Fare boxplot identifies potential high-value outliers.
- Gender shows a strong association with survival.
- Approximately 74.20% of female passengers survived compared with
  approximately 18.89% of male passengers.
- Passenger class also shows an association with survival.
- First-class passengers had a higher survival rate than second- and
  third-class passengers.
- Female passengers had higher survival rates across all passenger
  classes.
- First-class females had the highest survival rate at approximately
  96.8%.
- Age distribution shows passengers across a wide range of age groups.
- Correlation analysis was performed on numerical features.
- Pairplot visualization was used to compare relationships between
  numerical features.
- Sex, Pclass, and Fare provide useful information for studying
  passenger survival.
- Correlation and association do not necessarily imply causation.

## Conclusion

Exploratory Data Analysis was performed on the Titanic dataset using
Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

Descriptive statistics, histograms, boxplots, correlation analysis,
and pairplots were used to understand the dataset.

The analysis revealed noticeable differences in survival based on
gender and passenger class. Female passengers had a substantially
higher survival rate than male passengers, while first-class
passengers had a higher survival rate than second- and third-class
passengers.

The analysis also identified positive skewness and potential outliers
in the Fare feature.

Overall, EDA helped transform the raw Titanic dataset into meaningful
insights and provided a better understanding of the data before
applying machine learning models.
