# tedkorir-association-mini
# Association Rule Mining - Mini Assignment

This project simulates transaction data and applies Apriori algorithm to discover shopping patterns.

## Task Overview

1. Simulated 10 fake transactions with items like Milk, Bread, Eggs, etc.
2. Transformed the data using one-hot encoding.
3. Used the Apriori algorithm with min support = 0.3.
4. Generated association rules with confidence ≥ 0.7.

## Example Rule (from output)

**If a customer buys Milk, they are likely to buy Bread.**  
- Confidence: 0.8  
- This suggests placing Milk and Bread near each other in stores or offering combo deals.

## Tools Used

- Python
- pandas
- mlxtend
