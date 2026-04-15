# Principal Component Analysis on Digits Dataset

## Overview

This project demonstrates how to apply Principal Component Analysis (PCA) on the Digits dataset to reduce dimensionality while preserving important information. It converts high-dimensional pixel features into a smaller set of principal components for faster training, easier visualization, and efficient machine learning workflows.

## Dataset

The Digits dataset contains handwritten digit images represented as 8x8 pixel values.

* Total samples: 1797
* Features: 64
* Classes: 10 digits (0-9)

## Objectives

* Load and explore the Digits dataset
* Scale features before PCA
* Apply PCA for dimensionality reduction
* Visualize explained variance
* Train and evaluate a classifier

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Workflow

1. Load dataset
2. Train-test split
3. Feature scaling
4. Apply PCA
5. Train model
6. Evaluate performance

## Example Libraries

```python
from sklearn.datasets import load_digits
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.decomposition import PCA
from sklearn.linear_model import LogisticRegression
```

## Results

PCA helps reduce computation cost and noise while retaining most of the useful variance in the data.

## How to Run

1. Clone the repository
2. Install dependencies
3. Run the notebook or Python script

## License

This project is open for learning and educational use.
