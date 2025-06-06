#  Amazon Product Sales & Review Analysis

This project analyzes over **1,000 Amazon products** using Python and Pandas to uncover patterns in pricing, ratings, and customer reviews. The dataset includes detailed product information, user feedback, and discount data, helping us evaluate **consumer behavior**, **pricing strategy**, and **product performance**.

## 📥 Dataset Source

The dataset was sourced from **Kaggle**:  
🔗 [Amazon Sales Dataset by Karkavel Raja](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data)

##  Dataset Description

This dataset contains the following:
- Product IDs, names, categories, and images
- Actual and discounted prices
- Customer ratings and reviews
- Discount percentages
- Reviewer IDs and usernames
- Product and image links

> Designed to analyze customer opinions, pricing strategies, and discount effectiveness for Amazon products.

---

##  Project Objectives

-  **Clean and preprocess data**  
  Remove symbols, convert data types, check missing values, handle inconsistent formats

-  **Understand review content**  
  Explore review titles and texts for insights into customer satisfaction

-  **Calculate derived metrics**  
  Create new columns like `difference_price`, review category bins, and split product types

-  **Transform categorical data**  
  Split and standardize multi-level product categories

---

## Notebooks Overview

| Section | Description |
|--------|-------------|
| `1. Load & Inspect Data` | Load CSV, check types, view sample |
| `2. Clean Prices & Ratings` | Remove ₹, %, convert strings to numeric |
| `3. Handle Missing & Duplicate Entries` | Check `.isna()`, `.duplicated()` |
| `4. Split and Rename Categories` | Break category column into multiple features |
| `5. Rank Products by Rating` | Create rating bands: Poor, Average, Excellent |
| `6. Reviewer Analysis` | Split reviewer IDs and names from comma-separated strings |

---

##  Tools & Libraries Used

- `pandas` for data cleaning and wrangling
- `numpy` for numerical transformations
- `matplotlib / seaborn` (optional, for visualization)
- Jupyter Notebooks / Google Colab for interactive development

---

##  Sample Insights

- Some products had large discount gaps (> ₹1,500), yet received average ratings.
- A small number of ratings contained formatting issues (e.g., `'|'`) that were cleaned manually.
- Many product categories were nested (`Electronics|Accessories|Cables`), requiring transformation for proper analysis.

---

##  Getting Started

1. Clone this repo
2. Upload or place `amazon.csv` in the working directory
3. Run the notebook `amazon_analysis.ipynb` (or similar)
4. Explore product trends and pricing insights

---

##  Acknowledgements

- Dataset from Kaggle by [Karkavel Raja](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
- Analysis by Ananya Pandey

---


