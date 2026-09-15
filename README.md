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

## How to Run the Project

### 1. Clone the Repository

```bash

git clone <repository-url>
cd ai-programming-foundations

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
