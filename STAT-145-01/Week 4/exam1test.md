# Problem 2

1. Which variable is the predictor variable?
    Daily cigarettes.
    
2. Calculate the correlation value for these data:
    0.761

    1. Interpret the correlation value in the context of the problem.
        The correlation value says that there is a somewhat significant correlation.

3. Provide the equation of the regression line for this data.
    $$
    y=87.386-0.707x
    $$

4. Interpret the line of the slope, in the context of the problem.
    For every cigarette smoked daily, the age of death goes down by 0.707 years.

5. Calculate the value of $R^2$
    0.580

    1. Interpret the value of $R^2$ in the context of the problem.
        The value of $R^2$ suggests that a linear regression is not the best way to interpolate or extrapolate the data to the population.

6. Calculate the number of cigarettes smoked daily is 14, what do we predict is their age of death?
    $$
    y=87.386-0.707x\\
    y=87.386-(0.707*14)\\
    y=87.386-9.901\\
    y=77.485\approx77\ years
    $$

7. Calculate the residual for when 14 cigarettes are smoked daily. Show your work.
    $$
    e=68-77.485\\
    e=-9.485\ years
    $$

8. A residual plot is provided for this linear regression model. Can we assume a linear model is a valid model for these data? Explain.
    The residual plot shows that the linear model is not the best model, because of the wide spread in both directions. 

# Problem 3

1. Using the recall times for pleasant memories, calculate the following and fill in the blank row:

    | Mean  | $\sigma$ | Min  | Q1    | Median | Q3   | Max  | IQR   |
    | ----- | -------- | ---- | ----- | ------ | ---- | ---- | ----- |
    | 2.829 | 1.43     | 0.95 | 1.805 | 2.43   | 3.32 | 6.17 | 1.515 |

2. Calculate the lower and upper fences.
    $$
    Fence=Q_{1/3}\pm1.5*IQR\\
    LF=Q1-1.5*IQR;\ UF=Q3+1.5*IQR\\
    LF=1.805-1.5*1.515;\ UF=3.32+1.5*1.515\\
    LF=1.805-2.2725;\ UF=3.32+2.2725\\
    \overline{\underline{|LF=0.468;\ UF=5.593|}}
    $$

3. Interpret the lower and upper fences.
    The lower fence shows that there is no value that is an outlier below the mean. The upper fence says that the maximum is an outlier.

4. Does this data set have any outliers?
    The maximum is an outlier, because it is above the upper fence.

5. Create a Box Plot:
    ![img](data:image/png;base64,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)

6. Describe the shape of the distribution, and explain.
    The distribution appears to be skewed slightly left, with a single outlier.

7. Indicate the recall time that is typical, and explain why you chose this value.
    A typical recall time is between 3.32 and 1.805. I picked this range because it contains 68% of the data.

# Problem 4

1. Use a complete sentence and the context of the problem to interpret the sample mean.
    The students in the sample averaged a 531 points.

2. Explain why the empirical rule intervals and percentages can be applied to these data.
    The question states that the data is relatively bell-shaped.

3. About 68% of the students scored between what two values?
    493 and 569

4. Only 2.5% of students scored above _ 645 _ on the Math SAT.

5. Find and interpret the 84th percentile of scores in the context of the problem.
    84% of students scored under 569 points.

6. Your cousin earned a math SAT score of 528. Find the zscore of her math sat score. round to the nearest hundredth.
    $$
    Z={x-\overline{x}\over \sigma}\\
    Z={528-531\over 38}\\
    Z=-0.08
    $$
    

7. Interpret this Z-score. 
    This Z-score means that my cousin got ever so slightly worse than the average, but essentially scored the same.

8. Based on the Z-score, how did your cousin do?
    Well, but not amazing.

# Problem 5

1. An analyst has determined that both companies profit distributions are somewhat symmetric. Explain why this is reasonable.
    
2. Based on the comparative box plots which company has higher profits per employee, on average? Explain.
    Computer has a higher profit per employee on average, because the median is higher.![image-20200611181529943](exam1test.assets/image-20200611181529943.png)
3. Your colleague claims tha![image-20200611181529996](exam1test.assets/image-20200611181529996.png)t the aerospace companies profit data has much more variability than the computer data. Using a reliable measure of spread, explain why this is not true. 
    Computer has a larger IQR, so it is more variable.