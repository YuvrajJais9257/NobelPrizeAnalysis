## 📊 Nobel Prize Analysis

This notebook explores, cleans, and visualizes data on Nobel Prize winners.
Below is a brief summary of the operations performed in each step of the analysis.

---

### 🧰 Operations Summary

| Step | Operation                                                                  |
| ---- | -------------------------------------------------------------------------- |
| 1    | Install/upgrade Plotly for interactive visualization                       |
| 2    | Import required libraries, including `pandas` and `plotly`                 |
| 3    | Configure pandas to display floats with two decimal places                 |
| 4    | Load dataset from `nobel_prize_data.csv`                                   |
| 5    | Display shape of the dataset (rows, columns)                               |
| 6    | Print the year of the first Nobel Prize awarded                            |
| 7    | Count and print the number of duplicate values in the dataset              |
| 8    | Count and print the total number of missing (NaN) values                   |
| 9    | Provide reasoning about why some columns have missing values               |
| 10   | Remove duplicate entries to create a clean dataset                         |
| 11   | Convert `birth_date` column to datetime objects                            |
| 12   | Create `share_pct` column by parsing and computing prize share percentages |
| 13   | Display first few rows of the cleaned dataset                              |
| 14   | Count and print number of male laureates                                   |
| 15   | Import Plotly Express for visualization                                    |
| 16   | Filter dataset to include only female laureates                            |
| 17   | Iterate over filtered female laureates (possibly for display/analysis)     |
| 18   | Identify laureates who have won multiple times                             |
| 19   | Count and print the number of unique prize categories                      |
| 20   | Create a bar plot showing number of prizes per category using Plotly       |

---

## 📦 Dependencies

* Python
* pandas
* plotly

*(Install with `pip install -r requirements.txt` or as seen in the notebook)*

---

## 📁 Dataset

Make sure `nobel_prize_data.csv` is placed in the working directory.
This dataset should contain Nobel Prize laureate details such as names, categories, years, birth dates, and prize share.

---

## 📈 Visualizations & Insights

The notebook explores:

* Distribution of prizes by category
* Analysis of repeat winners
* Gender breakdown of laureates
* Prize share percentages

---

## ✅ How to Run

1. Clone this repository
2. Install dependencies
3. Open `NobelPrizeAnalysis.ipynb` in Jupyter Notebook / JupyterLab
4. Run cells step by step
