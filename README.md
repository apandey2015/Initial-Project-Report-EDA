# Project Title
Forecasting Electric Vehicle Adoption Using Machine Learning

# Executive Summary
Future electric vehicle (EV) adoption can be forecast by analyzing historical EV sales trends alongside the current number of EVs on the road. Historical sales data reveal how rapidly EV adoption has grown and how consumers have responded to improvements in technology, pricing, and government incentives. The current EV population reflects market acceptance and progress toward widespread adoption. When combined, these data provide a strong foundation for projecting future EV growth and support informed planning by policymakers, businesses, and utilities for charging infrastructure, energy demand, and long-term transportation needs.

# Rationale
Understanding future EV adoption is critical for effective planning and investment. Automakers need reliable forecasts to scale production, utilities must anticipate changes in electricity demand, and city planners must determine where and when charging infrastructure should be deployed. Poor forecasts could result in overinvestment, wasted resources, or infrastructure shortages that slow adoption.

This analysis transforms historical data into actionable insights about future EV demand. By using data-driven methods, the project supports better decision-making, more efficient allocation of resources, and a smoother transition to electric transportation.

# Research Question
How can historical EV sales patterns and the current EV population be used to forecast future electric vehicle adoption in the United States using machine learning techniques?

# Data Sources
https://www.kaggle.com/datasets/jainaru/electric-car-sales-2010-2024

# Methodology
Linear regression, Polynomial regression, Trend Analysis

# Results
<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/1a5d9a31-9318-476c-a000-aa119a16c037" />
<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/379de6c3-cc26-43b5-b35f-a67be8dc3a99" />
<img width="576" height="453" alt="image" src="https://github.com/user-attachments/assets/1b7bb08c-7ba5-4f0b-a19c-96001e5228c7" />
<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/ba0b62c5-ae05-4830-b09f-f45f00c39c17" />
The visual EDA shows that global EV adoption follows a clear diffusion pattern. EV sales grow slowly in the early years and accelerate sharply after 2019, while EV stock increases smoothly and rapidly as a cumulative measure of adoption. The widening gap between sales and stock reflects the accumulation effect typical of new technologies. Overall, the trends indicate that EVs have transitioned from an early adoption phase to a rapid growth phase globally.

<img width="579" height="453" alt="image" src="https://github.com/user-attachments/assets/d38d2f76-0457-48fc-ba8d-c07e1955901f" />
The graph shows that while the linear regression captures the general upward trend in EV sales, it does not fit the data well. It performs poorly in the early years and fails to capture the rapid growth in later years, indicating that EV sales grow in a nonlinear pattern rather than a linear one.

<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/9ac383d9-8a47-47a6-8778-bc7d294b645f" />
The graph shows that polynomial regression fits EV sales much better than linear regression. It captures the slow early growth and the rapid increase in recent years, showing that EV sales grow in a nonlinear way.

The exploratory analysis shows that global EV adoption follows a clear nonlinear growth pattern. Early years are characterized by very low sales and stock, indicating an initial adoption phase. From the mid-2010s onward, EV sales accelerate sharply, leading to rapid growth in cumulative EV stock. Linear regression captures the general upward trend but performs poorly at the beginning and during periods of rapid growth. In contrast, nonlinear (polynomial) regression fits the data much better by capturing the accelerating nature of EV adoption. Overall, the analysis confirms that EV adoption has moved from an early niche stage to a rapid expansion phase, and nonlinear models are more appropriate for analyzing and forecasting EV sales.

# Next steps
Repeat the analysis for major markets (e.g., US, China, EU).
Use GridSearchCV for SVR or Decision Tree and compare results with polynomial regression

# Outline of project
