# Handling-Skewness-of-the-Data
![image](https://user-images.githubusercontent.com/92606737/222619099-38033234-1c5a-4bae-9587-0c3296644206.png)

# What is Skewness of the data?
Skewness is a measure of the asymmetry of a distribution. A distribution is asymmetrical when its left and right side are not mirror images.

A distribution can have right (or positive), left (or negative), or zero skewness. A right-skewed distribution is longer on the right side of its peak, and a left-skewed distribution is longer on the left side of its peak:
![image](https://user-images.githubusercontent.com/92606737/222619252-4de0d028-05b0-4994-96d8-8d840f375153.png)



# Why Normal Distribution is important?
Transforming data into a normal distribution is important in machine learning for several reasons:
![image](https://user-images.githubusercontent.com/92606737/222619873-4705b99e-e05d-43d0-a4eb-7f652b3c230d.png)

- __Improved model performance__

     Many machine learning algorithms, such as linear regression and logistic regression, assume that the data is normally distributed. When the data is skewed, these algorithms may not perform as well and may produce biased or inaccurate results. Transforming the data into a normal distribution can improve the performance of these algorithms and lead to more accurate and reliable models.

- __Better feature scaling__
   
   Normalized data can help to improve the performance of some machine learning algorithms by reducing the impact of outliers and extreme values. Normalizing data can also help to improve the convergence of iterative algorithms such as gradient descent.

- __Better feature selection__
  
  Transforming data into a normal distribution can make it easier to identify important features that are correlated with the target variable. This is because normal distributions have a predictable and standardized shape that allows for easier analysis and interpretation.

- __Better interpretation__
    
   Normal distributions are easy to interpret and analyze. They have well-defined properties such as mean, variance, and standard deviation. This makes it easier to understand the data and draw meaningful conclusions.

- __Improved visualization__

   Normal distributions are easy to visualize and plot. This can help to identify patterns and relationships in the data that might be difficult to see in a skewed distribution.

In summary, transforming data into a normal distribution can improve the performance, interpretability, and visualization of machine learning models. However, it is important to choose the appropriate transformation based on the specific problem and the data itself. Additionally, it is important to assess the effectiveness of the transformation on the model's performance.


# Differenent methods to handle skewness of the data?
There are many methods that used in different conditions. Some are given below:
- __Log Transform__
   
   Log transformation is a common technique used in machine learning to transform skewed data into a more normal distribution. This can be particularly useful when working with numerical data in regression or classification problems.
   
   Log transformation is particularly useful when the data has a right-skewed distribution, where the majority of values are clustered on the left side of the distribution, and a few extreme values are on the right side. In this case, the transformation can make the data more symmetric and improve the performance of some statistical analyses that assume normality.

In regression problems, log transformation is often used to transform response variables that have a skewed distribution. This can help to stabilize the variance and improve the accuracy of the regression model. For example, if the response variable is income, which is typically right-skewed, taking the logarithm of the income values can help to normalize the distribution and improve the performance of the regression model.

In classification problems, log transformation can be used to transform skewed features. This can be particularly useful when using linear classifiers such as logistic regression, which assume that the features are normally distributed. Log transformation can also help to reduce the influence of outliers and improve the separation between classes.

It's important to note that log transformation should be used with caution and only when appropriate.

 
- __Sqare Root Transformation__ 

