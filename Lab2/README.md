# Practical Work No. 2 — Pandas: Working with Tables

**Author:** Andrii Melnykivskyi, group KN-41

## Description
This work covers the core Pandas structures (`Series` and `DataFrame`): creating a DataFrame from a dictionary, importing a CSV file, inspecting data (`head`, `tail`, `info`, `describe`), indexing with `loc` / `iloc`, filtering with boolean masks, sorting, and saving results to CSV. It also includes answers to the self-check questions and a bonus function that counts records per category.

## Dataset
`sales.csv` — a training dataset of coffee shop sales (100 transactions) with 6 columns: `date`, `datetime`, `cash_type`, `card`, `money`, `coffee_name`.

## Files
- `Melnykivskyi_Practice2.ipynb` — practical part (steps 1–8)
- `Zavdannya2_Melnykivskyi.ipynb` — individual tasks 1–7 and answers to the self-check questions
- `Dodatkove2_Melnykivskyi.ipynb` — bonus task ★ (`group_by_count` function)
- `sales.csv` — dataset
- `filtered_sales.csv`, `coffee_name_counts.csv` — saved results

## How to run
1. Upload `sales.csv` to your Google Drive (the `MyDrive` folder).
2. Open a notebook in Google Colab.
3. Run the cells in order; allow access to Google Drive when prompted.

Outside Colab, the notebooks fall back to the local files in the same folder.

## Requirements
Python 3, `pandas`, `numpy` (preinstalled in Google Colab).
