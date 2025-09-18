

````markdown
# Apriori Algorithm Market Basket Analysis

This project applies the **Apriori algorithm** to a supermarket transaction dataset to uncover association rules between items. It identifies shopping patterns, frequent item sets, and opportunities for cross-promotion or bundling.

## 📂 Project Structure
- `script/apriori_algorithm.Rmd` — R Markdown workflow including:
  - Data import and cleaning
  - Conversion of transactions into a sparse matrix
  - Rule mining with Apriori
  - Visualization and interpretation of results
- `dataset/Market_Basket_Optimisation.csv` — transaction dataset
- `docs/apriori_algorithm.html` — rendered HTML report viewable online

## 🛠️ Requirements
R and the following packages:

```r
install.packages(c("here", "arules"))
````

## 🚀 Viewing the Analysis

You can view the fully rendered report **without running R** here:
[Apriori Algorithm HTML Report](https://spoja-10.github.io/Apriori-Algorithm/apriori_algorithm.html)

## 📊 Example Output

Rules are displayed in the form:

```
{lhs items} => {rhs item}
```

Metrics include:

* **Support:** proportion of transactions containing both lhs and rhs
* **Confidence:** probability of rhs given lhs
* **Lift:** how much more likely rhs is purchased with lhs compared to chance

## 💡 Key Insights

* Shoppers who buy **mineral water + whole wheat pasta** are 6× more likely to also buy **olive oil**
* Nearly half of customers who buy **spaghetti + tomato sauce** also buy **ground beef**
* **Milk** frequently appears alongside frozen vegetables and soups
* Associations often reflect **meal-based shopping patterns**

## 📌 Recommendations

* Promote **meal kits** like “Spaghetti Bolognese Night” or “Healthy Pasta Pack”
* Adjust **shelf placement** (olive oil near pasta, beef near spaghetti sauce)
* Offer **milk promotions** with frozen or soup items
* Market using **complete meal patterns**, not individual products

## ✨ Author

Phenyo Morulane


