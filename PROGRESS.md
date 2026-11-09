# MLlearn — Progress Tracker

## Current Status

- **Current Phase:** Phase 2 — Supervised Classical Machine Learning
- **Current Milestone:** Linear Regression
- **Current Activity:** Final documentation and Git integration
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

### Phase 1 — Python Data Science and Jupyter

#### NumPy and pandas

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

#### Data Visualization

- [x] Matplotlib fundamentals
- [x] Object-oriented plotting API
- [x] Subplots and chart customization
- [x] Seaborn statistical visualizations
- [x] Histograms, KDE, boxplots, scatterplots, and heatmaps

#### Exploratory Data Analysis

- [x] Synthetic student dataset EDA
- [x] Univariate and bivariate analysis
- [x] Correlation analysis
- [x] Feature and target identification
- [x] Train/test splitting
- [x] Feature engineering
- [x] Preprocessing pipelines
- [x] Data leakage prevention

#### Student Performance Analysis — UCI Dataset

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

#### Phase 1 Experiment Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Mean baseline | 2.3946 | 3.1726 | -0.0322 |
| Early Linear Regression (without G1/G2) | 2.1564 | 2.8618 | 0.1602 |
| Late Linear Regression (with G1/G2) | 0.7651 | 1.2149 | 0.8487 |

**Important:** The late prediction experiment uses G1 and G2, which are prior-period grades. Its performance should not be confused with early prediction performance.

**Phase 1 Status: Completed and integrated.**

---

### Phase 2 — Supervised Classical Machine Learning

#### Linear Regression Fundamentals

- [x] Understood supervised learning and regression
- [x] Identified features (X) and target (y)
- [x] Understood the Linear Regression equation
- [x] Studied weights and bias
- [x] Understood prediction using model parameters
- [x] Studied Mean Squared Error (MSE)
- [x] Understood cost functions
- [x] Studied Gradient Descent
- [x] Derived weight and bias gradients
- [x] Understood learning rate and parameter updates
- [x] Investigated convergence and overshooting

#### Linear Regression From Scratch

- [x] Implemented prediction using NumPy
- [x] Implemented MSE calculation
- [x] Implemented gradient calculation
- [x] Implemented Gradient Descent training loop
- [x] Tracked training loss across epochs
- [x] Visualized the loss curve
- [x] Compared learned parameters with expected parameters
- [x] Compared scratch implementation with scikit-learn LinearRegression
- [x] Studied feature standardization
- [x] Investigated optimization behavior before and after scaling
- [x] Evaluated predictions on unseen test data

#### California Housing — Real-World Regression

- [x] Loaded the California Housing dataset
- [x] Inspected dataset structure and feature columns
- [x] Examined statistical summaries and distributions
- [x] Investigated target distribution
- [x] Identified target capping at 5.0
- [x] Performed correlation analysis
- [x] Investigated feature relationships
- [x] Created boxplots and examined potential outliers
- [x] Checked missing values and duplicate rows
- [x] Separated features and target
- [x] Created training and testing datasets
- [x] Built a StandardScaler and LinearRegression pipeline
- [x] Trained the model
- [x] Evaluated training and testing performance
- [x] Visualized actual versus predicted values
- [x] Performed residual analysis
- [x] Investigated heteroscedasticity and prediction errors
- [x] Interpreted standardized model coefficients
- [x] Generated predictions for new housing records
- [x] Documented dataset and model limitations

#### California Housing Experiment Results

| Metric | Training | Testing |
|---|---:|---:|
| MAE | 0.528628 | 0.533200 |
| MSE | 0.517933 | 0.555892 |
| RMSE | 0.719676 | 0.745581 |
| R² | 0.612551 | 0.575788 |

#### Key Findings

- Median income has the strongest individual correlation with median house value.
- Geographic features contribute substantially to the multivariable model.
- Training and testing performance are relatively close.
- Residual analysis indicates non-constant error variance.
- The target is capped at 5.0, limiting information about expensive properties.
- Linear Regression can produce predictions outside the observed target range.
- The model provides a useful baseline but does not capture all patterns in the dataset.

#### Linear Regression Notebooks

- [x] `04_linear_regression_from_scratch.ipynb`
- [x] `05_california_housing_regression.ipynb`

**Phase 2 Linear Regression Status: Learning and experimentation completed.**

## Remaining Tasks

### Linear Regression — Repository Integration

- [ ] Verify both notebooks execute successfully from fresh kernels
- [ ] Review notebook Markdown and conclusions
- [ ] Finalize README.md, ROADMAP.md, and PROGRESS.md
- [ ] Review staged Git changes
- [ ] Commit Linear Regression milestone
- [ ] Push feature branch
- [ ] Create Pull Request into develop
- [ ] Merge into develop
- [ ] Synchronize main with develop

## Next Milestone

### Phase 2 — Logistic Regression

After completing the Linear Regression Git integration:

- Understand classification versus regression
- Study binary classification
- Understand the sigmoid function
- Study decision boundaries
- Understand probability predictions
- Study the logistic loss function
- Implement Logistic Regression from scratch
- Use scikit-learn LogisticRegression
- Evaluate using classification metrics
- Perform practical experiments on a real dataset

Continue with KNN, Naive Bayes, Decision Trees, Random Forest, Gradient Boosting, and SVM according to ROADMAP.md.

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