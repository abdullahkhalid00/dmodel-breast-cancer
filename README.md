# Breast Cancer Detection 📊

A brief analysis and model creation for breast cancer detection (classification) using classic machine learning algoritms (SVM, decision trees, logistic regression, and ensemble methods).

## Description

The key question to entertain is; how can we classify breast cancer patients into Malignant (M) and Benign (B) groups? This analysis uses techniques like.

- Dimensionality Reduction
- Correlation Analysis
- EDA
- Machine Learning Classification

> More details can be found in [`analysis.ipynb`](notebook/analysis.ipynb).

### Results

Here's an image of the training results. It was quite surprising to see Logistic Regression performing this good.

![eval.png](/images/eval.png)

## Usage

Clone the repository and navigate to the root folder.

```bash
git clone <repo-link>
cd dmodel-breast-cancer
```

Create a `virutalenv` and activate it.

```bash
virtualenv env
source env/bin/activate
```

Install the necessary libraries from `requirements.txt`.

```bash
python3 -m pip install -r requirements.txt
```

Start the notebook in any IDE or directly from the terminal.

```
jupyter notebook
```

## Acknowledgements

The dataset used has been referred from [Kaggle](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset).

## Contribution

Feel free to open an issue or a pull request.
