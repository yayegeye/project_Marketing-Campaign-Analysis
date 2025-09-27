# Marketing Campaign Analysis
![ads](ads.png)

### Overview
Analyzed advertising performance on Facebook and Google AdWords to identify which platform delivers higher conversions and cost-effectiveness.

### Key Features
- Ad Views: Number of times the ad was displayed
- Ad Clicks: Number of clicks received
- Ad Conversions: Number of desired actions from clicks
- Cost Metrics: Cost per Ad, Cost per Click (CPC), Cost per Conversion
- Click-through Rate (CTR): Clicks / Views
- Conversion Rate: Conversions / Clicks

### Methods & Tools
- Data Cleaning & EDA: Pandas, NumPy, Matplotlib, Seaborn
- Statistical Analysis: t-test for hypothesis testing
- Predictive Modeling: Linear Regression (scikit-learn)
- Time Series Analysis: Cointegration test (statsmodels)

### Key Findings
- Conversions: Facebook outperforms AdWords (11.7 vs 6 conversions/day)
- Predictive Modeling: Linear regression model shows strong correlation (R² = 0.76) between clicks and conversions
- Cost Efficiency: Facebook lower cost per conversion ($8.07) compared to AdWords ($24.71)
- Long-term Trends: Spend and conversions are cointegrated for both platforms → stable ROI prediction

### Conclusion
- Facebook: Best for maximizing conversions and ROI
- AdWords: More predictable cost per conversion, efficient for CPC-sensitive campaigns
- Recommendation: Balanced ad spend allocation to leverage Facebook for volume and AdWords for cost efficiency
