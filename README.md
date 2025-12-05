# Food Deserts, Socioeconomic Factors, and Obesity Rates Across U.S. Counties

> Obesity is a complex public health issue influenced by a combination of behavioral, environmental, and socioeconomic factors. One area of particular interest is the role of food deserts (geographic areas with limited access to affordable and nutritious food) in shaping dietary patterns and health outcomes. Communities experiencing higher levels of food insecurity or limited access to healthy food options may face an increased risk of obesity.

>This project investigates the relationship between socioeconomic indicators, food desert components, and obesity rates. It aims to answer, How do socioeconomic factors and elements of food deserts relate to obesity rates? Multiple modeling approaches were applied, including stepwise regression and elastic net regression, to identify key predictors while addressing multicollinearity. Principal Component Analysis (PCA) was also explored to determine whether dimensionality reduction could improve model performance. The goal of this analysis is to quantify how different aspects of the food environment and socioeconomic context contribute to obesity risk.

>Data for this project were sourced from the USDA Food Environment Atlas, which compiles a wide range of indicators across categories such as health, food insecurity, socioeconomic status, retail stores, local access, and food assistance programs. Since the dataset contains measurements from multiple years, predictor variables were lagged to examine their association with obesity rates in 2022. 


---

## Project Overview

- **Objective:** To understand how component indicators of food deserts and socioeconomic factors relate to obesity rates.
- **Domain:** Socioeconomics and healthcare
- **Key Techniques:** Exploratory analysis of summary statistics and graphing (heatmaps, histograms, linear regression, residual plots); forward stepwise method for linear regression optimal parameter selection; elastic net; PCA; test and train data splitting.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks 
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** (https://www.ers.usda.gov/data-products/food-environment-atlas)
- **Description:** County level obesity rates, food access indicators, food insecurity, store types per capita, socioeconomic indicators, after cleaning ~3,000 counties.
- **License:** (if applicable)

---

## Analysis

The final reduced elastic net model achieved a moderate fit (R-squared Test=0.38), identified food insecurity (coefficient = 1.232) as the strongest positive driver of obesity, underscoring the critical role of food desert conditions. This effect was compounded by positive associations with access to convenience stores (0.505) and, unexpectedly, supercenters (0.682), suggesting that presence of large food outlets doesn't guarantee healthier outcomes. Conversely, higher median income (-0.420), a larger older adult population (-0.384), and greater access to grocery stores (-0.409) and specialized food stores (-0.206) acted as significant protective factors, highlighting the mitigating influence of socioeconomic status and access to diverse, nutritious food options. 

---

## Results

The project found that higher food insecurity, greater access to convenience stores, and supercenters were associated with higher obesity rates, suggesting that limited access to nutritious foods contributes to obesity. Conversely, higher median income, a larger older adult population, and greater access to grocery and specialized food stores were linked to lower obesity rates, highlighting protective effects of socioeconomic status and access to healthier food options. Overall, the findings indicate that both food environment characteristics and socioeconomic factors play a significant role in obesity risk. While the model captured a moderate proportion of the variation in obesity rates, additional behavioral, and environmental factors may improve model predictions. 

---

## Authors

- Emily Larson
- Jack Neton
- EJ Bergevin

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- - Python
- - jupyter notebook
- - pandas package
- - numby package
- - seaborn package
- - plotly package
- - scipy.stats packages
- - sklearn packages
- - mlxtend package
- Tutorials or papers referenced
- Inspiration or collaborators
