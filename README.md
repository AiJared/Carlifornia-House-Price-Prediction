# Carlifornia-House-Price-Prediction
This Data Science project predicts prices of houses in different areas of Carlifornia State based on various features extracted from the data.

These features include housing median age, total rooms, total bedrooms, population, households, ocean_proximity, median_income, longitude, latitude and median house value.

It also examines features that determine prices of houses in the State of Carlifornia

## Data

"housing.csv" dataset is the data used for this project.

It has 20640 rows by 10 columns.

## Data Preparation and Exploration

207 rows of Null values are dropped for easy fitting of algorithms to the model.

All plotted figures in this project are saved as png file images for future reference if need.

There are no duplicate values in the dataset

From checking for correlation, it is clear that the median_house_value is determined mostly by median_income, total_rooms, housing_median_age, total_bedrooms, households and population due to high degree of correlation to each other as show by the high concentration of blue colored values that are above 0.50. Other features are correlated with low degree as shown in the figure below.

![correlation](https://user-images.githubusercontent.com/78556152/210124663-659c64eb-8698-41a4-a048-8e694b888bc6.png)
