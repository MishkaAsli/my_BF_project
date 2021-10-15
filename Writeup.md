Design: 
Business Problem: Purchasing shoes for resell is currently done by “gut feeling” business rules. How can individual StockX shoe resellers maximize their revenue? The StockX website also currently shows stats on one shoe and not the stats in relation to other similar shoes.  This analysis will help optimize revenue for individual sellers on StockX.

Target Audience: Individuals wanting to optimize the price of shoes to resell. 

Data:
Dataset was provided by StockX and included the Order Date, Sale Price, Retail Price, and Shoe Style among other features.

Algorithm + Tools:
Exploratory Data Analysis was performed in Google Sheets. The EDA includes: vlookup, if statements, search statements, left statements, if error statements, and statements, concatenation, simple division, creating dummy variables, creating pivot tables, creating a correlation matrix. 
Tableau was utilized to visualize the data. 

Preliminary Analysis: Exploratory Analysis and visualization of the median return on investment of some of the Adidas and Nike shoes sold on StockX.

Future Analysis: Build a predictive model of Adidas and Nike shoe sales on StockX for a given colorway and shoe size, to inform future pricing and optimize revenue for individual sellers.

Impact Hypothesis: We want to optimize revenue of shoes individual sellers sell on StockX. We hypothesize that finding the shoes with the highest return on investments and then predicting the shoe price of future shoe releases will enable us to do that. We will use highest return on shoe investments and forecasting to reduce loss, and reduce guessing of which shoes to buy. 


Solution Path Option 1: Type: Prediction. Algorithm to Use: Regression. Error Metric: MAE (because the errors scale linearly). 
Solution Path Option 2: Type: Grouping/ Clustering (Cluster shoe styles/ color/buyer region to evaluate any comparisons and discover patterns) Algorithm to Use: K means clustering (partition dataset into K pre-defined distinct non-overlapping subgroups where each data point belongs to only one group) Error Metric: Sum of squared errors (the difference between the observed value and the predicted value. Measures the unexplained variability by the clustering)
 
Measures of Success:
Technical: 
MAE is less than $50. 
Non-Technical: 
Increase overall revenue by 20%. 
Decrease time spent searching for shoes by 25%.

Risks and Assumptions: 
Risks: 
Current market has some drastic changes like Covid. 
Celebrity unexpectedly wearing a shoe and raising the sale price of that shoe. Shoe company goes bankrupt and stops distributing shoes. 
Dataset doesn’t state the condition the shoe is in.
Assumptions: 
Currently popular shoes will remain popular. 



