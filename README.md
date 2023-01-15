# Market Basket Analysis Retail Dataset with Association Rules
This repository contain application of association rules for market basket analysis with retail dataset from Kaggle

# Dataset
The dataset could access here https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/code. It is containing retail transaction data that has 7 columns, they are InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID.
In this dataset, the data is limited only in December 2009 due to alignment with previous analysis (price elasticity analysis) and due to limited of resources

# Metrics Requirement
1. Minimum support 0.01. It means the item in 100 transaction at least the item is purchased 1 times.
2. Sort by the highest confidence, to see the popular associaton between items that people purchased
3. Lift > 1 that means item Y is likely to be bought if item X is bought

# Results Example
Antecedents Product: 'EDWARDIAN PARASOL NATURAL', 'PINK CHERRY LIGHTS', 'RED HANGING HEART T-LIGHT HOLDER', 'WOOD S/3 CABINET ANT WHITE FINISH', 'WOODEN PICTURE FRAME WHITE FINISH'

Consequents Product: ' WHITE CHERRY LIGHTS', 'BLACK/BLUE DOTS RUFFLED UMBRELLA', 'FANCY FONT HOME SWEET HOME DOORMAT', 'WHITE HANGING HEART T-LIGHT HOLDER'

From the most popular item that bought together (support = 0.010036, confidence =	1.0, lift =	99.642857), we gained insights as below:
1. People who purchased lights often buy two color together, the most popular is pink cherry and white
2. People who purchased umbrella with the type of edwardian parasol natural also bought black/blue dots ruffled umbrella
3. People who want to decor their home actually buy some product including cabinet, t-light, cabinet, doormat and picture frame.
4. Another interesting insight is they also bought them with matching color such as all white in this case

