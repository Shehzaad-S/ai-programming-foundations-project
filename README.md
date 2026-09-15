# AI Programming Foundations Project

## Project Description

This project explores the physicochemical properties and quality ratings of Portuguese Vinho Verde red and white wines. Using Python, Pandas, Matplotlib, and Seaborn, the project demonstrates a reproducible data analysis workflow including data ingestion, cleaning, exploratory data analysis (EDA), visualization, and interpretation.

## What I Built

- Loaded and combined the Wine Quality datasets.
- Performed data cleaning by removing duplicate records and adding wine type labels.
- Conducted exploratory data analysis using summary statistics, grouped analysis, and correlation analysis.
- Created visualizations to investigate relationships between wine characteristics and quality ratings.
- Summarized key findings, limitations, and assumptions.

## Dataset

**Wine Quality Dataset (Red and White Vinho Verde Wines)**
Source:

[Wine Quality Dataset (UCI Machine Learning Repository)](https://archive.ics.uci.edu/dataset/186/wine+quality)

Files used:

- winequality-red.csv
- winequality-white.csv

## Bias Awareness

Poor data cleaning can introduce bias and misleading conclusions into an analysis. For example, duplicate observations may disproportionately influence statistical summaries and visualizations, while improperly handling missing values or outliers can distort relationships between variables. In this project, duplicate records were removed before analysis to reduce the risk of repeated observations influencing the results. Although the dataset contained no missing values, care was taken to validate data quality before performing exploratory analysis.

## Future Machine Learning Workflow

If this project were extended into a machine learning workflow, additional preprocessing steps would likely be required. These steps could include feature scaling, train-test splitting, feature selection, and evaluation of class imbalance within the quality ratings. The exploratory analysis performed in this project identified alcohol content and density as potentially informative features that could be investigated further within supervised learning models. Classification and Regression tasks can be explored further with a reproducible ML pipeline workflow as a possible implementation strategy.

## Neural Network Preparation

Before training a neural network, the dataset would require additional preparation. Similar preprocessing steps taken for ML workflow would apply and the target variable would need to be defined as either a classification or regression objective. Additional experimentation would also be required to determine whether the available physicochemical measurements contain sufficient predictive information to support a neural network approach, which typically requires large amount of data to train.

## Agentic Automation Potential

Agentic AI systems could help automate portions of this workflow, including data ingestion, data validation, exploratory analysis, visualization generation, and reporting. An agent could identify data quality issues, generate statistical summaries, create visualizations, and produce draft analytical reports while still allowing a human analyst to review findings and make final decisions. Such automation could improve efficiency while preserving human oversight of analytical conclusions. We also need to consider if other automation tools would fit this problem similarly without the token cost of an AI agent (cron/MLflow for example)

## How to Run the Project

### 1. Clone the Repository

```bash

git clone <repository-url>
cd ai-programming-foundations-project

```

### 2. Create and Activate an Environment

Example using Conda:

```bash

conda create -n ai-foundations python=3.11
conda activate ai-foundations

```

Example using Python env (Windows cmd):

```bash

python -m venv .venv
.venv\Scripts\activate.bat

```

Please use operating system specific terminal commands for your system

### 3. Install Dependencies

Python version:
3.11

```bash

pip install -r requirements.txt

```

for conda envs:

```bash
conda env create -f environment.yml

```

### 4. Open the Notebook

Launch Jupyter Notebook:

Navigate and open file in your IDE or use Anaconda Navigator to launch notebook if using Conda

```
notebooks/data_workflow.ipynb

```

From the Terminal:

```bash
jupyter notebook
```

Open the notebook and run all cells from top to bottom.

## Requirements File

Generate the requirements file with:

```bash

pip freeze > requirements.txt

```

for conda export:

```bash

conda env export > environment.yml

```

The `requirements.txt` file is included in this repository for reproducibility.
