# Car-price
Predictive modelling of price of a car:
The objective of this project is to build a model that predicts the price of a car given a set of features. Intuitively the target variable is the cost price of cars and this cost depends on various factors, out of which 21 of them are considered in this experiment. These factors serve as the regressor or independent variables and they are mentioned below.

Categorical variables:
1. Make
2. Fuel type
3. Aspiration
4. Num_of_doors
5. Body style
6. Drive wheels
7. Engine location
8. Engine type
9. Num_of_cylinders
10. Fuel system

Quantitative variables:
1. Wheel_base
2. Length
3. Width
4. Height
5. Curb_weight
6. Engine_size
7. Compression_ratio
8. Horsepower
9. Peak_rpm
10. City_mpg
11. Highway_mpg

Here, few algorithms like linear regression, ridge, lasso, SVM and decision trees are used to fit and predict the data. From them, a suitable model with better evaluation metrics is chosen and its parameters are fine tuned for obtaining best results.

# EDA findings
Initially I did exploratory data analysis on the data and found interesting relationships.
1. Some factors like horsepower, engine size, length, peak rpm of a car were positively correlated with its price (i.e., as Horsepower increases , the price also increases)
2. City MPG and Highway MPG were negatively correlated with the price (when the mpg increases, price decreases)
3. The price of Diesel engine cars were relatively higher than the Petrol engine cars
4. The price of Rear wheel drive cars were relatively high than those of the front wheel.
