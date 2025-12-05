# Food Deserts, Socioeconomic Factors, and Obesity Rates Across U.S. Counties

> Obesity is a complex public health issue influenced by a combination of behavioral, environmental, and socioeconomic factors. One area of particular interest is the role of food deserts (geographic areas with limited access to affordable and nutritious food) in shaping dietary patterns and health outcomes. Communities experiencing higher levels of food insecurity or limited access to healthy food options may face an increased risk of obesity.

This project investigates the relationship between socioeconomic indicators, food desert components, and obesity rates. It aims to answer, How do socioeconomic factors and elements of food deserts relate to obesity rates? Multiple modeling approaches were applied, including stepwise regression and elastic net regression, to identify key predictors while addressing multicollinearity. Principal Component Analysis (PCA) was also explored to determine whether dimensionality reduction could improve model performance. The goal of this analysis is to quantify how different aspects of the food environment and socioeconomic context contribute to obesity risk.

Data for this project were sourced from the USDA Food Environment Atlas, which compiles a wide range of indicators across categories such as health, food insecurity, socioeconomic status, retail stores, local access, and food assistance programs. Since the dataset contains measurements from multiple years, predictor variables were lagged to examine their association with obesity rates in 2022. 


---

## Project Overview



- **Objective:** To understand how component indicators of food deserts and socioeconomic factors relate to obesity rates.
- **Domain:** Socioeconomics and healthcare
- **Key Techniques:** Exploratory analysis of summary statistics and graphing (heatmaps, histograms, linear regression, residual plots); forward stepwise method for linear regression optimal parameter selection; elastic net; PCA; test and train data splitting.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** (https://www.ers.usda.gov/data-products/food-environment-atlas)
- **Description:** Brief overview of the dataset features, size, and format
- **License:** (if applicable)

---

## Analysis



---

## Results

Include a short discussion of the findings and what they imply.

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
