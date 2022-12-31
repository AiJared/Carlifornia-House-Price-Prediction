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

![Screenshot 2022-12-31 092337](https://user-images.githubusercontent.com/78556152/210127401-fee3f7ff-4b96-4dd9-b354-811fdef24237.png)

## Data Visualization

from the histograms below, total_rooms, total_bedrooms, households, median_income, population and median_house_value are positively skewed evident by tails on the right side of distributions. Longitude and Latitude are bimodal as shown by two distinct peaks while the distribution of housing_median_age is random.

![house_price_data_visualization](https://user-images.githubusercontent.com/78556152/210125665-1b598e10-cb4d-46f9-99b1-834c6073547d.png)

