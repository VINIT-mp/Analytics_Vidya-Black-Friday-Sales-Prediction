# Analytics_Vidya-datahack

## BLACK FRIDAY SALES PREDICTION

## Objective: 
Building a model around the data which will help us predict the Sales forecasting of the data and derive insights from the previous data. The model was validated by RMSE Score


## Challenges Faced:
1. There were quite a few ambeguious data viz the "Occupation Data" data was masked.
2. The "Age" data was highly categorised.
3. Missing data was present in "Product_Category_2" and "Product_Category_3"


## Challenges Solved:
1. There was no way of getting around the "Occupation Data" hence I had to analyze the Value counts of the "Occupation" data
2. The "Age" data's categorization was further segmented into.
- (0-17)  == kids
- (18-25) == youth
- (26-35) == adults
- (36-45) == midage
- (46-50) == old age
- (51-55) == elderly
- (55+)   == senior
3. The "Product_Category_2" and "Product_Category_3" has 31.56% and 69.67% missing values (NaN) in them respectively. Since Product_Category_2" has fewer NAN values relatively, we will impute it using mean.
4. "Product_Category_3" which has higher(69.67%) was imputed by '0', since we dont want to disturd the pattern of the distribution  


## Observations: 
1. Age group 2 [Adults] perticularly males seem to contribute higher number of transactions of successful purchases
2. Customers Residing in the current city fro about 1 year have higher transaction count.
3. City Category '2' has highest transaction  count
4."Occupation" 4 0 7 have higher transaction counts respectively
