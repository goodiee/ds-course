# Data Science and Machine Learning Course

This repository contains my practical work, notes, and reports completed while following [mlcourse.ai](https://mlcourse.ai/), an open Machine Learning course from OpenDataScience led by [Yury Kashnitsky](https://yorko.github.io/).

The course combines machine learning theory with hands-on practice through lectures, mathematical explanations, programming assignments, and applied exercises. It covers the foundations of machine learning in a self-paced format. Neural networks and Generative AI are outside the main scope of the course.

For guidance on how to approach the learning materials, watch the [course introduction video](https://youtu.be/CPlYV_DryEo).

## Repository Structure

```text
training-data-science/
├── data/
├── notebooks/
│   ├── bagging_random_forest.ipynb
│   ├── decision_trees.ipynb
│   ├── eda_true.ipynb
│   ├── feature_engineering.ipynb
│   ├── linear_classification.ipynb
│   ├── pca_clustering.ipynb
│   ├── stochastic_gradient.ipynb
│   ├── t_data_visualisation.ipynb
│   ├── time_series.ipynb
│   └── xgboost.ipynb
├── report/
└── README.md
```

## Topics Covered

The notebooks in this repository cover the following topics:

- Exploratory data analysis
- Data visualization
- Feature engineering
- Decision trees
- Bagging and random forests
- Linear classification
- Stochastic gradient methods
- Principal component analysis and clustering
- Time-series analysis
- Gradient boosting with XGBoost

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/goodiee/ds-course.git
cd ds-course
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

### 3. Install the main dependencies

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn xgboost
```

### 4. Start Jupyter

```bash
jupyter notebook
```

Open the required notebook from the `notebooks` directory.

## Learning Approach

1. Review the relevant theory and course materials on [mlcourse.ai](https://mlcourse.ai/).
2. Open the corresponding notebook.
3. Run the notebook cells in order.
4. Study the visualizations and model results.
5. Modify parameters and compare outcomes.
6. Record conclusions in the `report` directory.

## Main Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost

## Course Attribution

The learning materials and course structure are based on [mlcourse.ai](https://mlcourse.ai/), created by OpenDataScience and led by [Yury Kashnitsky](https://yorko.github.io/). This repository is intended for educational practice and personal coursework.

## License

The original course materials remain subject to their respective terms and licenses. Code and notes created specifically in this repository may be reused according to the repository license, if one is added.
