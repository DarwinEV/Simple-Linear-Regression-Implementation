# Simple-Linear-Regression-Implementation
<h2>This is an implementation of Simple Linear Regression using food price to predict waiter tips.</h2>

- Preprocess:
  - Remove any data that is not meal price(x) or tip value(y) in order to only have 1 variable on each axis.
  - Manually find values on excel for r, total sum of squares(SST), squared error(SSE), Residual(SSR), p, f, CI, PI, z, std.dev., covariance/variance. 
  - Use excel Regression data analysis tool.
- Analysis:
  - Look at the significance between the two values by calculating Pearson's Correlation Coefficient(r).
  - See if the values p and f fall within the confidence level of 95%. If so the results are Significant.
  - consider the data distribution(skewness, kurtosis).
- Compare:
  - Compare excels regression calculation with the manual values
  - Compare manual predictions with the sklean LinearRegression() predictions using Squared Error.
  
---------- Conclusions ----------


- Sources:
  - Youtube: Brandon Foltz - Simple Linear Regression, zedstatistics, Quantitative Specialists
  - Khan Academy: AP®︎/College Statistics
  - Tools: https://www.ttable.org/, excel, Kaggle, Jupyter Notebooks
  - Dataset: sns.load_dataset('tips')
  - Libraries: sklearn, pandas, Seaborn, matplotlib
