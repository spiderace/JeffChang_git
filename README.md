In this python code, we breakdown and analyze the acceptance rate of Bar Coupons by different types of customer in the data.

First, we had to clean the data and remove any unnecessary data.  There is column for "car".  Most of the field in this column is NaN field.  Since the customers are mostly driving when the coupon is offered, so customers do have access to a car, therefore, I believe that the "car" field is not necessary.  Therefore, I removed the "car" column
Second, there are a number of fields with NaN or null data.  This would cause problem during analysis, so it is also removed.

I have tried to analyze a number of different factors in predicting acceptance rate of the bar coupon, but the most useful predictor of coupon acceptance is how many times the customer visit a bar in a month?If a customer visits a bar more than once a month, then 69~70% the customer would accept the bar coupon.  Every other factor fails in comparison to predict coupon acceptance.

The code and the data are all located in the right folder path.
