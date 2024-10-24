# Project Roadmap

## Notebook

- ### EDA (3 points)
- **Dataset  Overview:**

  - Number of features, casting, types
  - Missing Values
  - Duplicates
    &nbsp;
- **Univariate Analysis:**

  - Descriptive Stats
  - Distribution (variance)
  - Categorical - countplots
  - Outliers
  - Data incoherencies
  - Missing values classification
    &nbsp;
- **Bivariate Analysis:**

  - Correlations / Chi-square
  - Pairplots - Drill down pairwise interesting relationships
  - Hued hists, barcharts and anova for categorical vs numerical
    &nbsp;
- **Mulvariate Analysis:**

  - PCA
  - Clustering techniques (e.g., K-means, hierarchical) to identify patterns or groups
    &nbsp;
- **Outlier detection:**

  - Univariate - z-scores if normal, IQR if not
  - Multivariate - [Isolation Forest](https://www.youtube.com/watch?v=O9VvmWj-JAk) or [DBSCAN](https://www.youtube.com/watch?v=RDZUdRSDOok) (dependes on look of the data - dbscan for condensed points with obvious visual separation from other few points)

---

- ### Data Pre-process (5 points)

  - Handle Missing values
  - Apply transformations to improve feature distribution (check for outliers after)
  - Handle outliers
  - Feature Engineering - create and analyze new features
  - Categorical Encoding (maybe makes sense to bin first)
  - Scale numerical features
- ### Feature Selection (3 points)

  - Try 2 approaches: filter, wrapper (embedded not needed, not too many vars)
- ### Model Training and Assessment (4 points)

  - Try Naive Bayes and Logistic regression ( maybe NN depends on time)

## Report (5 points - 2 pages)

- Detail your intended contents for each section of your final report.
- Present and explain the rationale of your open-ended section:
  - Create an analytics interface that returns a prediction when new inputs are given - [steamlit app](https://alejandro-ao-streamlit-cancer-predict-appmain-uitjy1.streamlit.app/) that allows new prediction and data exploration. If best model allows interpertation, allow exploring.
