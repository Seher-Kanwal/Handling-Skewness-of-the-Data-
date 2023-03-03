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
