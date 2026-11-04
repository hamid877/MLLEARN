# MLlearn — Progress Tracker

## Current Status

- **Current Phase:** Phase 1 — Python Data Science and Jupyter
- **Current Milestone:** Student Performance Analysis
- **Current Activity:** Final notebook verification and repository integration
- **Project:** MLlearn

## Completed

### Environment and Project Setup

- [x] Project initialized using uv
- [x] Python 3.12 environment configured
- [x] JupyterLab installed and verified
- [x] NumPy, pandas, Matplotlib, Seaborn, and scikit-learn installed
- [x] Git repository initialized
- [x] main and develop branches established
- [x] Project roadmap established

### NumPy and pandas

- [x] NumPy array creation and properties
- [x] Dimensions, shape, axes, and data types
- [x] Indexing and slicing
- [x] Boolean masking
- [x] Views and copies
- [x] Broadcasting and vectorization
- [x] pandas Series and DataFrames
- [x] Filtering, sorting, and grouping
- [x] Missing-value handling
- [x] Data validation and type conversion

### Data Visualization

- [x] Matplotlib fundamentals
- [x] Object-oriented plotting API
- [x] Subplots and chart customization
- [x] Seaborn statistical visualizations
- [x] Histograms, KDE, boxplots, scatterplots, and heatmaps

### Exploratory Data Analysis

- [x] Synthetic student dataset EDA
- [x] Univariate and bivariate analysis
- [x] Correlation analysis
- [x] Feature and target identification
- [x] Train/test splitting
- [x] Feature engineering
- [x] Preprocessing pipelines
- [x] Data leakage prevention

### Student Performance Analysis — UCI Dataset

- [x] Retrieved and inspected the UCI Student Performance dataset
- [x] Investigated dataset structure and data types
- [x] Checked missing values and duplicates
- [x] Investigated distributions and potential outliers
- [x] Analyzed categorical and numerical features
- [x] Studied relationships between G1, G2, and G3
- [x] Defined early and late prediction scenarios
- [x] Created a shared train/test split
- [x] Built numerical and categorical preprocessing pipelines
- [x] Established a DummyRegressor baseline
- [x] Trained Linear Regression models
- [x] Compared early and late prediction performance
- [x] Evaluated MAE, RMSE, and R²
- [x] Investigated prediction errors and residuals
- [x] Interpreted model coefficients
- [x] Compared OneHotEncoder configurations
- [x] Investigated an extreme prediction error
- [x] Created residual and Q-Q diagnostic plots

## Current Experiment Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Mean baseline | 2.3946 | 3.1726 | -0.0322 |
| Early Linear Regression (without G1/G2) | 2.1564 | 2.8618 | 0.1602 |
| Late Linear Regression (with G1/G2) | 0.7651 | 1.2149 | 0.8487 |

**Important:** The late prediction experiment uses G1 and G2, which are prior-period grades. Its performance should not be confused with early prediction performance.

## Remaining Phase 1 Tasks

- [ ] Restart the notebook kernel and execute all cells successfully
- [ ] Verify notebook reproducibility
- [ ] Review notebook markdown and conclusions
- [ ] Finalize repository documentation
- [ ] Review Git changes and commit relevant files
- [ ] Merge the completed work into develop

## Next Phase

Phase 2 — Supervised Classical Machine Learning.

Begin with a deeper study of Linear Regression, then progress through KNN, Naive Bayes, Decision Trees, Random Forest, Gradient Boosting, and SVM.

## Learning Rules

- Follow ROADMAP.md sequentially.
- Teach one concept at a time.
- Explain intuition before implementation.
- Include mathematical foundations and practical experiments.
- Implement algorithms from scratch where useful.
- Understand what happens behind library abstractions.
- Verify understanding before advancing.
- Prevent data leakage.
- Use appropriate evaluation metrics.
- Keep this project independent of ModelForge.
