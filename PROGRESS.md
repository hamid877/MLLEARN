# ML Learning Lab — Progress Tracker

## Current Status

- **Project:** MLlearn
- **Current Phase:** Phase 2 — Supervised Classical Machine Learning
- **Completed Algorithms:** Linear Regression, Logistic Regression, K-Nearest Neighbors
- **Current Algorithm:** Naive Bayes
- **Environment:** Python 3.12, uv, JupyterLab
- **Frameworks:** NumPy, pandas, Matplotlib, Seaborn, scikit-learn

## Completed Phases

### Phase 1 — Python Data Science and Jupyter

- [x] Python and Jupyter fundamentals
- [x] NumPy fundamentals
- [x] pandas fundamentals
- [x] Matplotlib and Seaborn
- [x] Exploratory Data Analysis
- [x] Feature engineering and preprocessing
- [x] Train/test splitting and data leakage
- [x] Student Performance Analysis project
- [x] California Housing regression preparation

### Phase 2 — Supervised Classical Machine Learning

#### Linear Regression

- [x] Regression fundamentals
- [x] Linear regression mathematics
- [x] Mean Squared Error and cost functions
- [x] Gradient Descent
- [x] NumPy implementation from scratch
- [x] Feature standardization
- [x] Scikit-learn implementation
- [x] California Housing regression experiment
- [x] Residual analysis and evaluation metrics

#### Logistic Regression

- [x] Classification fundamentals
- [x] Sigmoid function and probability prediction
- [x] Binary Cross-Entropy / Log Loss
- [x] Gradient derivation and Gradient Descent
- [x] NumPy implementation from scratch
- [x] Confusion matrix, precision, recall and F1
- [x] Classification threshold analysis
- [x] Breast Cancer Wisconsin dataset experiment
- [x] Scikit-learn comparison and inference

#### K-Nearest Neighbors (KNN)

- [x] KNN intuition and instance-based learning
- [x] Euclidean distance calculation
- [x] Majority voting
- [x] NumPy implementation from scratch
- [x] Reusable KNN classifier
- [x] Feature scaling and data leakage
- [x] K selection and overfitting/underfitting
- [x] Scikit-learn KNeighborsClassifier
- [x] Multiclass classification using Wine dataset
- [x] Accuracy, precision, recall, F1 and confusion matrix
- [x] Cross-validation for K selection
- [x] Uniform and distance-weighted voting
- [x] Euclidean vs Manhattan distance
- [x] New-observation inference

**KNN Experimental Results**

- Dataset: Wine classification
- Observations: 178
- Features: 13
- Classes: 3
- Train/test split: 80:20
- Best tested K: 17
- Mean 5-fold cross-validation accuracy: 97.91%
- Final test accuracy: 100% (36/36)
- Distance-weighted KNN test accuracy: 100%
- Manhattan distance test accuracy: 97.22%

Note: Results apply to the particular split and experiment; they do not establish universal model performance.

#### Naive Bayes
-[x] Gaussian Naive Bayes
-[x] Multinomial Naive Bayes
-[x] CategoricalS Naive Bayes


## In Progress

### Phase 2 — Next Algorithm
- [ ] Decision Trees
- [ ] Random Forest
- [ ] Gradient Boosting
- [ ] Support Vector Machines

## Future Phases

- Phase 3 — Unsupervised Learning
- Phase 4 — Evaluation and Reliable ML Experimentation
- Phase 5 — Deep Learning with PyTorch
- Phase 6 — Modern Architectures and Transformers

## Learning Rules

- Follow ROADMAP.md sequentially.
- Teach one concept at a time.
- Explain mathematical intuition before implementation.
- Implement important algorithms from scratch before using scikit-learn.
- Use real datasets and proper train/test evaluation.
- Prevent data leakage through correct preprocessing and pipelines.
- Explain evaluation metrics and experimental results.
- Maintain reproducible notebooks.
- Update documentation after every substantial milestone.
- Use feature branches, commits and pull requests.
- Keep MLlearn independent of ModelForge.