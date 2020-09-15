# Car-Price-Prediction-
A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. 

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. 

The company wants to know:

Which variables are significant in predicting the price of a car.

How well those variables describe the price of a car.

It is basically an automobile datasets where we perform the Linear Regression Model, machine learning to plot the data and visulize which variable for most effective to find or predict the price of a car.

In this dataset we analyze the data then we perform the task for visuliasing, firstly clean the data then spliting the columns name (like car_company) than after remove the uncessary columns then fixed the invalid values(there are some error in car-company name so we fixed the car name)

some columns values are string format so we convert the data into numeric format (like doornumber, cylindernumber etc..) and counting the each and every columns vaues and also ploting the risk rating(value +3 three indicating the auto is risky and -3 is pretty safe).

we visuliaze the numerical as well as categorical variable after visualising some relevant column we find the following situation:

1. In the subpot graph the plot seemed to be right-skewed i.e most of the price values below (15000).
2. There are the significant difference between the mean and the median of the price  distribution.
3. 85% of the prices are  below from 18500 whereas the remaining 15% price are between 18500 and 45500.
4. Price is  highly positively correlated  with carwidth,curbweight,enginesize,horsepower etc.
5. Price is negatively correlated with symboling, citympg, peakmpg and highwaympg.
6. The cars having high mileage may fall in the  economy.
7. There are many independent variable which are highly correlated.

In the Categorical visualisation, we find the some point:

1. toyota is highly favored company.
2. gas fueled cars are more then diesel.
3. sedan is the most preferable car. 
4. ohc is most favored engine type.
5. ohc and ohcf is the lowest price range.
6. Jaguar,Buick and Porsche seem to have highest price.
7. diesel has higher average price than gas.
8. hardtop and convertible have higher average price than sedan,wagon and hatchback.
9. Doornumber vairable not affecting the price nuch.there is significant difference between them.
10. std is less price than the turbo.

In the numerical data visualisation, the following things come in 

1. carlength, carwidth and curbweight seem to have highely positively correlation with price.
2. carheight doesn't have any significant with price.

In the Bivariate analysis we find then that the High range car prefered idi or mpfi fuelsystem.

After that we perform the data preparation than spliting the data int train and test and rescalling the data.

Then finally perform the Model building and RFE,VIF and Residual Analysis after that making prediction and evaluation.

Final Conclusion of the prediction 

1. R-squared and Adj. R-squared - (0.896 and 0.891)- 89% (Variance explained).
2. F-statistic and Prob (F-statistic) - (195.2 and 2.92e-64), Model fit is significant and explained 89% variance is
   is just not by chance.
3. p-values for all the coefficient seem to be less than the significance level 0.05. It mean that all the 
   predictions are statstically sigificant.
   
Then finally we find  the columns/variable that are significant for predicting the price of a car.  The following columns are

enginesize    
carwidth    
enginetype_rotor    
car_company_bmw    
enginelocation_rear    
car_company_renault




