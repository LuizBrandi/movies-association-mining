# MovieLens 1M Association Rules Mining

This project explores the **MovieLens 1M** dataset and extracts association rules from user preferences using **FP-Growth**.

## Project goal

Identify movie co-consumption patterns from positive interactions, where a positive interaction is defined as:

- `Rating >= 4`

## Main notebook

- `movies_mining.ipynb`

The notebook includes:

1. Exploratory Data Analysis (EDA)
2. Transactional transformation (user -> list of liked movies)
3. Frequent itemset mining with FP-Growth
4. Rule extraction and filtering (support, confidence, lift)
5. Support sensitivity analysis


## Quick start

1. Create and activate a Python environment.
2. Install dependencies described on the pyproject file.
3. Open and run `movies_mining.ipynb` from top to bottom.
