`Phase 1 — Python Data Science and Jupyter
Objective: Become comfortable working with datasets, numerical operations, data manipulation, and visualization before learning algorithms.
Module	Topics	Practical output
1.1	JupyterLab, cells, kernels, execution order	Working notebook
1.2	NumPy arrays, dimensions, shapes, dtypes	NumPy experiments
1.3	Indexing, slicing, Boolean masking	Array manipulation
1.4	Vectorization and broadcasting	Numerical experiments
1.5	NumPy mathematical operations	Statistical calculations
1.6	pandas Series and DataFrames	Tabular data manipulation
1.7	Filtering, sorting, grouping, aggregation	Data analysis
1.8	Missing values, duplicates, data types	Clean dataset
1.9	Matplotlib fundamentals	Visualization notebook
1.10	Seaborn and statistical plots	Statistical visualizations
1.11	Exploratory Data Analysis	Complete EDA
1.12	Features, targets, train/test split, leakage	Prepared ML dataset
Phase project: Student Performance Analysis

You'll analyze student performance data and investigate:
- Does studying longer correlate with better marks?
- Which variables are associated with performance?
- Are there missing or unusual values?
- How do we identify patterns using visualizations?
- How would we prepare this dataset for machine learning?
Completion checkpoint: You should be able to independently load, inspect, clean, manipulate, visualize, and prepare a dataset.

Phase 2 — Supervised Classical Machine Learning
Objective: Understand how machines learn from labeled examples and how different algorithms make predictions.

We'll follow this order:
Module	Algorithm	Main concepts
2.1	Linear Regression	Lines, coefficients, residuals, least squares
2.2	Logistic Regression	Sigmoid, probability, decision boundaries
2.3	K-Nearest Neighbors	Distance, similarity, K selection
2.4	Naive Bayes	Bayes' theorem, conditional probability
2.5	Decision Trees	Entropy, information gain, Gini impurity
2.6	Random Forest	Bagging, ensemble learning, feature importance
2.7	Gradient Boosting	Boosting, sequential error correction
2.8	Support Vector Machines	Hyperplanes, margins, kernels

For every algorithm, we will follow the same learning structure:
1. What problem does it solve?
2. How does it work intuitively?
3. What is the mathematical foundation?
4. What assumptions does it make?
5. How does the algorithm learn?
6. How do we implement it from scratch where appropriate?
7. How do we implement it using scikit-learn?
8. How do we visualize its behavior?
9. How do we evaluate it?
10. When should we use it, and when should we avoid it?
Phase project: Predict a real-world outcome using multiple algorithms and compare their performance.

You'll learn why a more complicated algorithm isn't necessarily a better algorithm.

Phase 3 — Unsupervised Learning
Objective: Learn how to discover patterns in data without providing predefined target labels.
Module	Algorithm	Concepts
3.1	K-Means	Centroids, distances, inertia
3.2	Hierarchical Clustering	Dendrograms, agglomerative clustering
3.3	DBSCAN	Density, core points, noise
3.4	PCA	Variance, eigenvectors, dimensionality reduction
We'll investigate:
- What makes clustering different from classification?
- How can we determine the number of clusters?
- Why does feature scaling matter?
- How do we measure clustering quality?
- How can we reduce hundreds of features to a smaller representation?
Phase project: Customer segmentation using clustering.

Phase 4 — Model Evaluation and Reliable Experimentation
This phase is especially important. An algorithm can produce predictions and still be a bad model.

We'll study:
Module	Topics
4.1	Regression metrics: MAE, MSE, RMSE, R²
4.2	Classification metrics: accuracy, precision, recall, F1
4.3	Confusion matrices and ROC-AUC
4.4	Training, validation, and testing
4.5	Cross-validation
4.6	Bias, variance, underfitting, overfitting
4.7	Feature scaling and categorical encoding
4.8	Pipelines and ColumnTransformer
4.9	Hyperparameter tuning
4.10	Class imbalance
4.11	Data leakage and leakage-safe evaluation
4.12	Reproducibility, random seeds, baseline comparisons

We'll also learn professional experimentation practices:
- Keep experiment configurations documented.
- Establish simple baseline models.
- Compare models under identical conditions.
- Record evaluation metrics.
- Investigate incorrect predictions.
- Separate training decisions from final test evaluation.
Phase project: Build a reliable model comparison experiment.

Phase 5 — Neural Networks and Deep Learning
Objective: Understand how neural networks learn, starting from a single neuron and progressing toward multilayer architectures.
Module	Topics
5.1	Tensors and multidimensional data
5.2	Perceptrons and artificial neurons
5.3	Weights, biases and linear transformations
5.4	Activation functions
5.5	Loss functions
5.6	Gradient descent
5.7	Chain rule and backpropagation
5.8	Multilayer Perceptrons
5.9	PyTorch tensors and autograd
5.10	Dataset, DataLoader and training loops
5.11	CNNs
5.12	RNNs
We'll use PyTorch only after understanding the mathematics behind neural networks.

You will implement:
- A simple neuron using NumPy.
- A small neural network with manual forward propagation.
- Gradient calculations.
- A training loop using PyTorch.
- An image classifier using CNNs.
- A sequence-based model using RNNs.
Phase project: Image classification using a neural network.

Phase 6 — Modern Architectures
Objective: Understand the architectures and learning techniques behind modern AI systems.
Module	Topics
6.1	Autoencoders
6.2	Encoder-decoder architecture
6.3	Attention mechanisms
6.4	Self-attention
6.5	Transformer architecture
6.6	Positional encoding
6.7	BERT and encoder-based models
6.8	GPT and decoder-based models
6.9	Supervised vs self-supervised learning
6.10	Transfer learning
6.11	Fine-tuning pretrained models
6.12	Practical Transformer implementation

Phase project: Fine-tune a pretrained Transformer for a practical NLP task.

We will not begin this phase until the preceding foundations are complete.