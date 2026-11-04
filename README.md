# MLlearn

A hands-on machine learning learning lab focused on understanding machine learning from fundamentals to modern deep learning.

The objective is to understand:
- How machine learning algorithms work.
- The mathematical intuition behind them.
- When and why to use different algorithms.
- How to implement algorithms and evaluate them correctly.
- How to conduct reproducible ML experiments.

This project prioritizes understanding over simply calling library functions.

## Learning Roadmap

1. Python Data Science and Jupyter
2. Supervised Classical Machine Learning
3. Unsupervised Machine Learning
4. Model Evaluation and Reliable Experimentation
5. Deep Learning with PyTorch
6. Modern Architectures and Transformers

See [ROADMAP.md](ROADMAP.md) for the detailed curriculum and [PROGRESS.md](PROGRESS.md) for current progress.

## Tech Stack

- Python 3.12+
- uv
- JupyterLab
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- PyTorch (introduced in the deep learning phase)

## Repository Structure

```text
mllearn/
├── notebooks/
│   ├── 01_numpy_pandas.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_student_performance_analysis.ipynb
│   └── practice/
│       ├── matplotlib_practice.ipynb
│       └── seaborn_practice.ipynb
├── src/
│   └── mllearn/
│       └── __init__.py
├── README.md
├── ROADMAP.md
├── PROGRESS.md
├── pyproject.toml
├── uv.lock
├── .python-version
└── .gitignore