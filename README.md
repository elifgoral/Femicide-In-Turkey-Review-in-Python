# Femicide in Turkey Dataset Statistical Review in Python

## Goal of Project
The subject of the project is the examination of basic probability and statistics terms using a dataset. I chose the dataset about femicide in Turkey. Data are recorded information from 2008 to 2020. Some of them are described as undetected. Analyzes such as mean, variance, max, min, sorting were made about the dataset.

## Important Methods For Statistical Data Analysis
|Years |Total Death|
|------|-----------|
2008 | 65
2009 | 123
2010 | 194
2011 | 121
2012 | 139
2013 | 229
2014 | 291
2015 | 295
2016 | 282
2017 | 348
2018 | 403
2019 | 427
2020 | 193

### Mean Analyze
It is known as the average. It is obtained by dividing the sum of the numbers in the list by the number of items. The mean is useful in determining the overall trend of a data set. Another advantage of mean is that it is very easy and fast to calculate. 

<a href="https://www.codecogs.com/eqnedit.php?latex=mean&space;=&space;\frac{&space;65&space;&plus;&space;123&space;&plus;&space;194&space;&plus;&space;121&space;&plus;&space;139&space;&plus;&space;229&space;&plus;&space;291&space;&plus;&space;295&space;&plus;&space;282&space;&plus;&space;348&space;&plus;&space;403&space;&plus;&space;427&space;&plus;&space;193&space;}{13}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?mean&space;=&space;\frac{&space;65&space;&plus;&space;123&space;&plus;&space;194&space;&plus;&space;121&space;&plus;&space;139&space;&plus;&space;229&space;&plus;&space;291&space;&plus;&space;295&space;&plus;&space;282&space;&plus;&space;348&space;&plus;&space;403&space;&plus;&space;427&space;&plus;&space;193&space;}{13}" title="mean = \frac{ 65 + 123 + 194 + 121 + 139 + 229 + 291 + 295 + 282 + 348 + 403 + 427 + 193 }{13}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=mean&space;=&space;239" target="_blank"><img src="https://latex.codecogs.com/gif.latex?mean&space;=&space;239" title="mean = 239" /></a>

### Median Analyze
Median returns the middle value after sorting the list.  If our data contains outliers such as 1000, we usually prefer to use median. Because mean easily affected by outliers. In this situation mean does not provide the accuracy.
 
  | 65 | 121 | 123 | 139 | 193 | 194 | 229 | 282 | 291 | 295 | 348 | 403 | 427 |
  |----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
                                      
### Variance and Standard Deviation
Standard deviation and variance are fundamental mathematical concepts that play important roles in the financial industry, economics, and investment. Using Standard Deviation we have a "standard" way of knowing what is normal, what is very large or very small. Standard deviation is one of the primary methods for analysts, portfolio managers and advisors use to determine risk. When the group of numbers is close to the mean, the investment is less risky; When the group of numbers is far from the mean, the investment carries greater risk to a potential buyer.

### Regression Analyze
α : regression constant : the point where the regression line intersects the y-axis

β : regression coefficient :The expected change in the dependent variable versus a 1-unit change in the independent variable. B > 0 : there is a correct relationship. B < 0 : there is an inverse relationship

ε : error

y : the dependent variable :

x : the independent variable

Regression analysis is used to determine the relationship between 2 or more variables with a cause-effect relationship and to make predictions about that subject using this relationship. For example, we can think of this as an increase in expenses as income increases. In this example, the cause is an increase in revenue and the result is an increase in expenses. Income is the independent variable and expenses are the dependent variable. Another example is the relationship between working time and a passing grade. The reason here is the duration of the study, while the result is the grade of success. Working time is the independent variable, grade is the dependent variable. 

Observation: As GDP decreases, the number of deaths increases. In the first table, there was a regular decrease in gdp between 2013 and 2019. When we analyze the number of deaths, we can observe the increase. When we look at the estimated values calculated by regression, we can observe the same increase. Since the regression method is an error-prone method, a difference is observed between the estimated and actual calculated values. But the increase and decrease hypothesis is confirmed.

![image](https://user-images.githubusercontent.com/42415419/123837320-63fc0980-d913-11eb-9bce-4f59ddb62b4b.png)

![image](https://user-images.githubusercontent.com/42415419/123837330-66f6fa00-d913-11eb-9923-8957a425b032.png)

![image](https://user-images.githubusercontent.com/42415419/123837340-69595400-d913-11eb-99c9-8c07be60565e.png)

![image](https://user-images.githubusercontent.com/42415419/123837353-6cecdb00-d913-11eb-82a1-a94b46a802f5.png)

![image](https://user-images.githubusercontent.com/42415419/123837367-6eb69e80-d913-11eb-8bfc-20670360b93d.png)


![image](https://user-images.githubusercontent.com/42415419/123833111-b1c24300-d90e-11eb-9ba1-c1e88d6a5b23.png)


### Correlation Analyze
Correlation analysis; The relationship between the variables is a statistical method that provides information about the direction and severity of this relationship. The correlation coefficient gives information about the direction of the variables and how the interactions are. The mathematical relationship between two or more variables is analyzed by "Regression Analysis" and the direction and degree of the relationship is examined by "Correlation Analysis". The correlation coefficient is the measure of the linear relationship between two variables. between -1 ≤ r ≤1. A correlation coefficient approaching 0 indicates the presence of a weak relationship between the variables. If the variables increase or decrease together, there is a positive relationship, and if one variable increases and the other decreases, there is a negative relationship.

Hypothesis;

𝐻_0 : p = 0  -> no relationship

𝐻_𝑠 : p ≠ 0 -> relationship

The significance of the correlation coefficient is tested using the t-test, according to the n-2 degrees
of freedom, according to the significance level given within the procedures below. Test statistics;
It is calculated with;

![image](https://user-images.githubusercontent.com/42415419/123833241-d1596b80-d90e-11eb-8419-157d68a8db65.png)

When 𝑡_𝐻 > 𝑡_(𝛼:𝑛−2)   : 𝐻_0 will be rejected and 𝐻_𝑠 will be accepted 

So; It will be seen whether the crelationship between the variables.
orrelation coefficient r is statistically significant and there is a
Let’s test the correlation coefficient we found above at the 0.05 significance level.
𝐻_0 : p = 0 (The correlation coefficient is insignificant.)
𝐻_𝑠  : p ≠ 0 (The correlation coefficient is important.)

![image](https://user-images.githubusercontent.com/42415419/123833564-27c6aa00-d90f-11eb-9b84-09353e6acf8c.png)

![image](https://user-images.githubusercontent.com/42415419/123833575-2b5a3100-d90f-11eb-9a36-af37e1ee25c9.png)

![image](https://user-images.githubusercontent.com/42415419/123833583-2e552180-d90f-11eb-96f5-3b573f5ad03a.png)

![image](https://user-images.githubusercontent.com/42415419/123833586-30b77b80-d90f-11eb-97f6-49f535a49f2f.png)

![image](https://user-images.githubusercontent.com/42415419/123833600-3319d580-d90f-11eb-809b-72c99baaf99c.png)

![image](https://user-images.githubusercontent.com/42415419/123837227-44fd7780-d913-11eb-8811-8b7f8beb0531.png)


## Comments
Experiencing physical or psychological violence has no age, gender, ideology or religion. Violence is violence and a crime, regardless of who is used for what reason. We must be against all forms of violence. Neither verbal, physical, nor psychological violence can have an explainable side, nor can it be justified. The real power emerges with the joint work of the mind and the heart. The intimidation that  is tried to be given with the power of the wrist is ineffectualness. The culprit is unclean minds, wicked hearts, and lack of justice.

## Results
Number of deaths by age of murdered women

![image](https://user-images.githubusercontent.com/42415419/123837446-855cf580-d913-11eb-825a-12fe7261cf51.png)

![image](https://user-images.githubusercontent.com/42415419/123837852-fef4e380-d913-11eb-9b94-3725e2444a41.png)


Number of death by protection order

![image](https://user-images.githubusercontent.com/42415419/123837456-87bf4f80-d913-11eb-8791-03c2d5b24d36.png)

![image](https://user-images.githubusercontent.com/42415419/123837838-fb615c80-d913-11eb-8835-0fbd311c1a06.png)


Number of Deaths by Killing Way

![image](https://user-images.githubusercontent.com/42415419/123837521-9a398900-d913-11eb-9bef-2b96f1a1c8f3.png)


Maximum Number of Death of year According to City

![image](https://user-images.githubusercontent.com/42415419/123837531-a291c400-d913-11eb-9167-a65525d44741.png)


Number of Death by Status of killer

![image](https://user-images.githubusercontent.com/42415419/123837554-a9b8d200-d913-11eb-8c6c-a6e0f878cad2.png)

![image](https://user-images.githubusercontent.com/42415419/123837805-f3092180-d913-11eb-9fac-cfb12b3d2b3b.png)


Number of Deaths by Killer

![image](https://user-images.githubusercontent.com/42415419/123837577-b0dfe000-d913-11eb-9c9e-3dd691096950.png)

![image](https://user-images.githubusercontent.com/42415419/123837767-e97fb980-d913-11eb-95eb-92a494557689.png)


Number of Deaths by reason

![image](https://user-images.githubusercontent.com/42415419/123837605-b9d0b180-d913-11eb-9773-4ca4032b0a13.png)


Classification according to Region in Turkey

![image](https://user-images.githubusercontent.com/42415419/123837651-c6550a00-d913-11eb-92f9-6f1a3f7fb463.png)


![image](https://user-images.githubusercontent.com/42415419/123837752-e389d880-d913-11eb-969b-c5386b772976.png)




Dataset are taken from https://www.kaggle.com/bradurak/femicide-in-turkey-20082020-english-dataset

References
1) https://academy.datawrapper.de/article/136-histogram-min-max-median-mean
2) https://www.bigskyassociates.com/blog/bid/356764/5-Most-Important-Methods-For-Statistical-Data-Analysis
3) https://www.veribilimiokulu.com/korelasyon-analizir-nedir/
4) https://www.youtube.com/watch?v=jwGE7A-q9Xk


