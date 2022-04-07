### Introduction to Data Science

# Introduction to Data Science - Practical Exam (50%)

**Dataset:** air_quality_4_boroughs_2020.csv / hourly_wage_by_borough_2020.csv / ethic-group-by-borough_2020.csv

**Model:** Linear regression (Scikit-learn)

**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn

***

### Project:
This task was to explore a dataset of hourly London air quality in 2020 for 4 locations in separate boroughs and create a Jupyter Notebook that provides some insightful summary of the contents of the dataset. Doing data wrangling adding two other datasets displaying hourly wage and ethnic makeup by borough  to support air quality insights and visualising the data. Finally, investigating relationships between variables and building a prediction model using linear regression.



### Summary:

- The dataset is a collection of air quality readings for the boroughs of Sutton, Hackney, Lewisham and Barking and Dagenham.

• One of the largest parts of cleaning the dataset was to replace the missing values. There were missing values for the NO, NO2 and NOX for all sites which were replaced with each borough's category mean.

• According to initial information the highest peak of the year was documented in Sutton for all categories and the lowest point in NO. Barking and Dagenham have the lowest NO2 points and Hackney has the lowest NOX point.

• Overall, Sutton has the highest readings in all categories and Barking and Dagenham has the lowest.

• The monthly trend is similar in all boroughs with a spike in late January and appearing lowest during spring time.

• The boroughs with the largest proportion of ethnic minority groups has the least pollution

• The boroughs with the lowest hourly wages have the least pollution. There is a correlation between higher hourly wages and more pollution.
