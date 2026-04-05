# Stock Market Sentiment Analysis (Nifty 50)

## Abstract
This project explores the relationship between investor sentiment and stock market performance using Nifty 50 data. Sentiment is quantified using trading indicators such as returns, volatility, and trading volume. Statistical and visual analyses reveal correlations between sentiment shifts and stock returns. The study applies ANOVA and Regression Analysis to test hypotheses and measure predictive relationships. Results indicate that market sentiment significantly influences short-term market dynamics.

---

# Introduction
The stock market is influenced not only by economic fundamentals but also by investor psychology. This project analyzes how sentiment—reflected through price movements, trading volume, and volatility—affects stock returns in the Nifty 50 index.

Using data analytics and visualization techniques, the study identifies behavioral patterns influencing financial decisions. The insights obtained provide a foundation for predictive modeling and risk assessment in financial analytics.

---

# Literature Review
Behavioral finance research highlights the impact of investor sentiment on stock valuation.

- Baker & Wurgler (2007) identified sentiment-driven mispricing in equity markets.
- Kumar & Lee (2006) linked retail investor sentiment to stock return co-movements.

Recent studies integrate social media and textual sentiment for real-time analysis. This project adapts these concepts to the Indian market using numerical indicators derived from trading data.

---

# Methodology

### Data Processing
Nifty 50 stock data was analyzed using Python.

Key libraries used:
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Workflow
1. Data Cleaning and Preprocessing  
2. Sentiment Labeling (Positive, Neutral, Negative)  
3. Exploratory Data Analysis (EDA)  
4. Statistical Testing  
5. Visualization of trends and relationships

Key indicators analyzed:
- Daily Returns
- Volatility
- Trading Volume

These metrics were used to compute sentiment scores.

---

# Data Techniques Used

## ANOVA (Analysis of Variance)
ANOVA was used to test whether mean stock returns differ significantly across sentiment categories.

Formula:

F = (SS_between / df_between) / (SS_within / df_within)

This helps determine whether sentiment classification has a statistically significant impact on returns.

## Regression Analysis
Regression models were used to predict stock returns using sentiment and trading indicators.

General model:

Return = β₀ + β₁(Sentiment) + β₂(Volatility) + β₃(Volume) + ε

Both simple and multiple regression models were applied.

---

# Exploratory Data Analysis (EDA)

EDA was performed to understand relationships between variables.

Visualizations included:
- Correlation matrices
- Distribution plots
- Sector-level comparisons
- Sentiment-based return distributions
- Volatility analysis
- Time-series style visual exploration

These visualizations helped reveal patterns in market sentiment and trading activity.

---

# Results and Discussion

The ANOVA test confirmed statistically significant differences in mean returns across sentiment groups.

Results:
- F-statistic ≈ 8500
- p-value < 0.001

This indicates that sentiment classification has a meaningful influence on stock performance.

Regression models further showed that sentiment is a strong predictor of returns.

Model performance:
- Adjusted R² between **0.12 – 0.22**

Including volatility and trading volume improved explanatory power, highlighting the combined influence of investor psychology and market dynamics.

---

# Conclusion

This project demonstrates a clear relationship between investor sentiment and market outcomes in the Nifty 50 index.

Key findings:
- Positive sentiment correlates with higher average returns
- Negative sentiment is associated with market downturns
- Sentiment indicators can provide useful signals for short-term market behavior

These insights can assist traders, analysts, and financial researchers in understanding behavioral patterns in stock markets.

---

# Future Work

Future research could extend this analysis by incorporating:

- Social media sentiment (Twitter, news sentiment)
- Macroeconomic indicators
- Longer time-series data
- Advanced machine learning models

These enhancements could provide deeper insights into investor behavior and financial market dynamics.
