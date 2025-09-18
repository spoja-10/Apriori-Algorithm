# Apriori Algorithm Market Basket Analysis

This project applies the **Apriori algorithm** to a supermarket transaction dataset in order to uncover association rules between frequently purchased items. The results help identify product groupings, customer shopping patterns, and potential opportunities for cross-promotion or bundling.

## 📂 Project Structure
- `apriori_algorithm.Rmd` — R Markdown file containing the full workflow:
  - Data import
  - Conversion of transactions into a sparse matrix
  - Rule mining using Apriori
  - Visualization and interpretation of results
- `dataset/Market_Basket_Optimisation.csv` — the transaction dataset used.

## 🛠️ Requirements
The analysis was written in **R** and requires the following packages:
https://spoja-10.github.io/Apriori-Algorithm/apriori_algorithm.html
```r
install.packages(c("here", "arules"))


