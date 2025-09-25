# EDA Practice and Notes
This repository is for practicing Exploratory Data Analysis (EDA).

## Topics
- **1. [Data Handling](1_data_handling)**
  - Array & DataFrame creation, indexing, slicing
  - Reshaping, merging, concatenation
  - GroupBy, pivot, melt, stack/unstack
  - Handling duplicates
  - Working with dates, times, strings

- **2. Data Cleaning**
  - **Missing Values**
    - Detection: `isna()`, `notna()`, summary tables
    - Handling:
      - Complete case analysis / listwise deletion
      - Imputation (mean, median, mode)
      - KNN imputation (using Euclidean distance)
      - Missing not at random → arbitrary values
      - Automatic selection of imputers, missing indicator
      - Categorical imputation
      - SQL-based handling (if dataset in DB)
  - **Duplicates & Data Types**
    - Detect and remove duplicates
    - Convert column types, handle categorical vs numeric
  - **Outliers**
    - Detection:
      - Z-score method
      - IQR method
      - Percentile method
      - Visual: boxplots, scatter plots
    - Removal or capping

- **3. Exploratory Data Analysis (EDA)**
  - **Summary Statistics**
    - Mean, median, mode, variance, standard deviation
    - Quantiles, skewness, kurtosis
    - Correlation matrices (Pearson, Spearman)
  - **Univariate Analysis**
    - Histograms, density plots, boxplots, violin plots
    - Frequency tables for categorical features
  - **Bivariate Analysis**
    - Scatter plots, correlation heatmaps
    - GroupBy and aggregation for comparisons
  - **Multivariate Analysis**
    - Pairplots, joint plots
    - Dimensionality reduction for visualization (optional PCA)
  - **Visualization Tools**
    - Matplotlib, Seaborn, Plotly
    - Interactive visualizations for dashboards

- **4. Data Transformation (EDA-focused)**
  - **Normalization & Scaling**
    - Standardization (z-score)
    - Min-max scaling
  - **Function Transformations**
    - Log transformation
    - Power transformation
  - **Binning & Binarization**
    - Convert continuous → categorical
    - Threshold-based features
  - **Regression Checks**
    - Regression after transformations to check linearity
  - **Feature Construction for Analysis**
    - Splitting columns (date-time → day/month/week)
    - Derived columns for better insights

- **5. Advanced Statistical EDA**
  - Hypothesis testing basics (for EDA context)
    - t-tests, chi-square tests, ANOVA
  - Detection of relationships
    - Correlation vs causation
  - Handling missing data patterns
    - MCAR (Missing Completely at Random)
    - MAR (Missing at Random)
    - MNAR (Missing Not at Random)
