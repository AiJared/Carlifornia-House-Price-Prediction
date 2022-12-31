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

![Screenshot 2022-12-31 092833](https://user-images.githubusercontent.com/78556152/210127559-7fe02023-b30c-450c-b9db-fd33ae57c6fb.png)

## Training the Model

Data is split into training and testing sets. Median_house_value variable is assigned to "Y" for prediction while the rest except ocean_proximity assigned to "X" during training and testing. Ocean_proximity is dropped because it is categorical and also there are location coordinates (longitude and latitude) which works well on behalf of ocean_proximity. However, if there weren't location coordinates then ocean_proximity would have been very usefull.

80% of the data is used for training while the remaining 20% used for testing. This ensures that the model has enough dataset to train on for a desirable accuracy.

Four algorithms are used to fit and train the model; Linear Regression, Support Vector Machine for Regression, Random Forest for regression and Decision Tree for regression.

Below are the different results from different algorithms:

#### Linear Regression Algorithm

![Screenshot 2022-12-31 094500](https://user-images.githubusercontent.com/78556152/210127951-1de04780-4378-49a0-9652-0240239ddb12.png)

#### Support Vector Machine Algorithm

![Screenshot 2022-12-31 094853](https://user-images.githubusercontent.com/78556152/210128034-502026f0-21fa-4429-b8ef-b3644c01826a.png)
