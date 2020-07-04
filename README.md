# Analytics_Vidya-datahack

## BLACK FRIDAY SALES PREDICTION

# Objective:
            Building a model around the data which will help us predict the Sales forecasting of the data and derive insights from the previous data. the data was validated by
            RMSE Score
            
            
# Challenges Faced:
             * There were quite a few ambeguious data viz the "Occupation Data" data was masked.
             * The "Age" data was highly categorised.
             * Missing data was present in "Product_Category_2" and "Product_Category_3"
             
# Challenges Solved:
              * There was no way of getting around the "Occupation Data" hence I had to analyze the Value counts of the "Occupation" data
              * The "Age" data's categorization was further segmented into (below) since there was a strong correlation between sales figures and age
				 
                    0-17 == kids
                   18-25 == youth
                   26-35 == adults
                   36-45 == midage
                   46-50 == old age
                   51-55 == elderly
                   55+   == senior
                   
              * The "Product_Category_2" and "Product_Category_3" has 31.56% and 69.67% missing values (NaN) in them respectively. Since "Product_Category_2" has fewer NAN values                  relatively, we will impute it using mean.
              * The "Product_Category_3" which has higher(69.67%) was imputed by '0', since we dont want to disturb the pattern of the distribution
