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
Explore the notebooks:
Open .ipynb files in Jupyter Notebook or Google Colab

Follow step‑by‑step instructions in Markdown and execute code cells along the way

📚 Content Overview
Getting Started: Introduction to pandas Series and DataFrame data structures

Reading Data: Load CSV, JSON, Excel, and other file types

Fundamentals: Indexing, slicing, selecting, filtering

Cleaning & Wrangling: Handle missing values, text normalization, type conversion, removing duplicates

Aggregation & Grouping: Use groupby, pivot_table, and aggregation functions

Merging & Reshaping: Combine datasets using merge, join, concat, and reshape with melt, pivot

Time Series Operations: Date parsing, rolling windows, resampling (if applicable)

Visualization: Quick plots with pandas and integration with Matplotlib/Seaborn (if included)

🛠️ Installation & Dependencies
Make sure you have Python 3.x installed. Then:

bash
Copy
Edit
pip install pandas matplotlib seaborn
If you're using Jupyter or Colab, most dependencies like pandas may already be pre-installed.

💡 Usage Example
python
Copy
Edit
import pandas as pd

df = pd.read_csv('data/sample.csv')
df_clean = df.drop_duplicates().fillna(method='ffill')
summary = df_clean.groupby('category')['value'].mean()
print(summary)
df_clean.plot(kind='line', x='date', y='value')
🧪 Exercises (Optional)
Some notebooks may include hands-on exercises—try solving them before checking solutions!

🤝 Contributing
Contributions are welcome:

Add examples or extend tutorials

Submit pull requests or open an issue

Improve code, documentation, or add new sections

📄 License
This project is open-source. [Add your preferred license here, e.g., MIT License.]
