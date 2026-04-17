# hallucination-detection-project

# How to Use This Project

## Step 1: Install Required Libraries

Run this in terminal:

```
pip install pandas numpy scikit-learn tensorflow torch transformers datasets tqdm
```

---

## Step 2: Run Dataset File

Go to:

```
notebooks/dataset.ipynb
```

Run all cells.

This will:

* Load dataset (SQuAD)
* Prepare and save data

---

## Step 3: Run Main Project File

Go to:

```
notebooks/project.ipynb
```

Run all cells.

This will
* Generate answers using model
* Clean data
* Create labels (correct / hallucinated)
* Train models
* Show results

---

## Step 4: Check Output

All results will be saved in:

```
data/processed/
```

You will find:

* Final dataset
* Features dataset
* Model results

---

## Notes

* Run `dataset.ipynb` first
* Then run `project.ipynb`
* Do not change folder structure

---
