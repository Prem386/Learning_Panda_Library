# Learning Panda Library 🐼

A hands-on **pandas learning library** featuring tutorials, examples, and exercises to help beginners sharpen their data manipulation skills using Python’s pandas.

---

## 🚀 What It Is

Learning Panda Library is designed to teach pandas fundamentals through practical examples. Whether you're just getting started or looking to solidify your pandas knowledge, this repo includes structured walkthroughs, exercises, and real-world use cases to help you learn by doing.

---

## ✅ How To Use

### Clone the repository:
```bash
git clone https://github.com/Prem386/Learning_Panda_Library.git
cd Learning_Panda_Library
```
---
### Open the Notebooks:
- Use **Jupyter Notebook** or **Google Colab** to open the `.ipynb` files.
- Follow the step-by-step Markdown instructions and run code cells as you go.

---
## 📚 Content Overview

- **Getting Started**: Series and DataFrame basics
- **Reading Data**: CSV, Excel, JSON
- **Data Cleaning**: Handling missing values, type conversion
- **Indexing & Filtering**: Slicing, querying
- **Aggregation**: `groupby`, `pivot_table`
- **Merging**: `merge`, `concat`, `join`
- **Time Series**: Parsing dates, resampling
- **Visualization**: With pandas, Matplotlib, or Seaborn

---
## 🛠️ Installation

Install dependencies (if not already installed):

```bash
pip install pandas matplotlib seaborn
```
---

#### Sample Usage Code Block

You hinted at usage earlier. Include a minimal working example.


## 💡 Example Usage

```python
import pandas as pd

df = pd.read_csv('data/sample.csv')
df_clean = df.drop_duplicates().fillna(method='ffill')
summary = df_clean.groupby('category')['value'].mean()
print(summary)
```
## 📄 License

This project is open-source. [MIT License](LICENSE)
