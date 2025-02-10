# Dallas Animal Shelter Data Analysis

This project explores the factors influencing the duration of stay for animals in shelters. Conducted using **R**, the analysis employs various statistical models, including **Poisson Regression** and **Negative Binomial Regression**.

## Methods
- **Poisson Regression** was initially used due to the count-based nature of the response variable. However, over-dispersion in the data invalidated the Poisson model's assumptions.
- **Negative Binomial Regression** was chosen to handle the over-dispersion and provided a better fit for the data.

## Conclusion
The project highlights the importance of model diagnostics in selecting the appropriate statistical methods. In this case, the Negative Binomial Model outperformed the Poisson model due to the presence of over-dispersion.