# Pricing Mobile Phones
Data exploration, feature engineering, and model building for smartphone price prediction.
In my second classification project, I evaluated the dataset of a mobile phone company that had several features and the selling price of 2000 mobile phones. There was a separate dataset for the test dataset that contained 1000 mobile phone information. The target variable was the selling price, which was reported in 4 categories; the higher the number of categories, the higher the price was. The main steps after importing the dataset were as follows: <br>
## Data cleaning: <br>
There were no missing or duplicate values in this dataset. I also checked for potential outliers. There were some potential outliers in a few of the columns, which I illustrated by using box plots and IQR percentiles. 
## EDA: <br>
I illustrated the analysis of this dataset in three types: univariate, bivariate, and multivariate analysis. In univariate analysis, I drew count plots for categorical features and scatter plots for continuous features. Then, I used histograms to visualize the distribution of each feature. I used a heatmap and pairplot for bivariate and multivariate analysis, respectively. The RAM column (the capacity of the RAM in MB) had the highest correlation with the selling price. 
## Data preprocessing and preparation for modeling: <br>
normalization using the min-max scaler method. The final range was 0-1. In order to facilitate the modeling, I defined functions for each type of algorithm and defined variables including max depth and test size. 
## Machine learning modeling: <br>
I ran the model with test sizes from 0.1 to 0.4 and different max depths to achieve the best performance. The metrics for each model are summarized in the output. The highest accuracy was related to the SVM algorithm with more than 0.97 accuracy.
