# 📊 Data Science Foundations

Complete hands-on learning notebooks for **Pandas**,**NumPy**,**Polars**,**Plotly**,**Rich**,**SQL** and **DuckDB** —
built through structured practice, chapter by chapter.  
Every chapter includes concept explanations, working code, and a dedicated practice set.

> 🔄 Actively updated as learning progresses toward freelance Data Science.

---

## 📚 Pandas — Complete Reference Notebook
> 12 Chapters | Practice Sets Included

| Chapter | Topic | Key Methods |
|---------|-------|-------------|
| 1 | Introduction to Pandas | `pd.DataFrame()`, `pd.__version__` |
| 2 | DataFrame Basics | `head()`, `tail()`, `describe()`, `info()` |
| 3 | Saving & Loading Data | `to_csv()`, `read_csv()`, `read_excel()` |
| 4 | Rows & Columns Selection | `loc[]`, `iloc[]`, boolean masking |
| 5 | Add, Update & Delete | `drop()`, `sort_values()` |
| 6 | Working with Dates | `to_datetime()`, `.dt` accessor, `Timedelta` |
| 7 | Missing Values | `fillna()`, `dropna()`, `ffill()`, `bfill()` |
| 8 | GroupBy & Aggregation | `groupby()`, `agg()`, `transform()`, `apply()` |
| 9 | Concat & Merge | `pd.concat()`, `pd.merge()` |
| 10 | AI-Assisted Coding | Prompting strategies, `query()` |
| 11 | Duplicate Values | `duplicated()`, `drop_duplicates()` |
| 12 | Reshape | `melt()`, `pivot()`, `pivot_table()` |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ali-datasmith/data-science-foundations/blob/main/pandas/pandas_complete.ipynb)

---

## 📚 NumPy — Complete Reference Notebook
> 8 Chapters | Practice Sets Included

| Chapter | Topic | Key Methods |
|---------|-------|-------------|
| 1 | Lists vs NumPy | `np.array`, `np.mean` |
| 2 | Creating Arrays | `zeros`, `ones`, `arange`, `eye`, `randint` |
| 3 | Array Properties | `shape`, `size`, `ndim`, `dtype`, `astype` |
| 4 | Mathematical Operations | `sum`, `mean`, `std`, `median`, `percentile` |
| 5 | Indexing & Slicing | Boolean masking, fancy indexing |
| 6 | Important Functions | `reshape`, `flatten`, `concatenate`, `split` |
| 7 | Broadcasting & Vectorization | Scalar × array, `np.newaxis`, one-hot encoding |
| 8 | Handling Missing Values | `isnan`, `nanmean`, `nan_to_num`, `isinf` |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ali-datasmith/data-science-foundations/blob/main/numpy/numpy_complete.ipynb)

---
## 🐻 Polars — Complete Reference Notebook
> 8 Chapters | Pandas vs Polars Benchmark Included

| Chapter | Topic | Key Methods |
|---------|-------|-------------|
| 1 | Installation & Setup | `!pip install polars`, `pl.__version__` |
| 2 | Creating DataFrames | `pl.DataFrame()`, `pl.read_csv()` |
| 3 | Select & Filter | `select()`, `filter()`, `pl.col()` |
| 4 | Adding & Modifying Columns | `with_columns()`, `.alias()` |
| 5 | GroupBy & Sort | `group_by()`, `.agg()`, `sort()` |
| 6 | Join & Concat | `join()`, `concat()` |
| 7 | Lazy vs Eager Execution | `.lazy()`, `.explain()`, `.collect()` |
| 8 | Polars vs Pandas Benchmark | **Polars 6x faster** on 1M rows |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ali-datasmith/data-science-foundations/blob/main/polars/polars_learning.ipynb)

---
## 📊 Plotly — Complete Reference Notebook

> 6 Chapters | Polars + Plotly Dark Theme Included

| Chapter | Topic | Key Methods |
|---------|-------|-------------|
| 1 | Installation & Setup | `import plotly.express as px`, `import polars as pl` |
| 2 | Loading DataFrames | `pl.DataFrame()`, sample sales / trend / scatter data |
| 3 | Bar Chart | `px.bar()`, `x=`, `y=`, `title=`, `template=` |
| 4 | Line Chart | `px.line()`, `markers=True`, trend visualization |
| 5 | Scatter Plot | `px.scatter()`, `size=`, `color=`, relationship analysis |
| 6 | Layout Customization | `fig.update_layout()`, axis labels, dark theme |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ali-datasmith/data-science-foundations/blob/main/plotly/plotly_learning.ipynb)

---
## 🎨 Rich for Data Science — Professional CLI Reference

> 3 Essential Chapters | Terminal Styling & Progress Tracking

| Chapter | Topic | Key Methods |
|---------|-------|-------------|
| 1 | Beautiful Prints | `from rich import print` for colored, nested data inspection |
| 2 | Structured Tables | `Table()`, `add_column()`, `add_row()` for grids |
| 3 | Progress Tracking | `track(iterable)` for live status bars in loops |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ali-datasmith/data-science-foundations/blob/main/rich/rich_learning.ipynb)

---
# 🦆 DuckDB + SQL — Complete Reference Notebook

> **8 Lessons | Polars vs SQL Comparison Included**

| Lesson | Topic | Key Methods |
|--------|-------|-------------|
| 1 | Installation & Connection | `duckdb.connect(':memory:')`, `con.execute()` |
| 2 | SELECT & WHERE | `SELECT col FROM df WHERE condition` |
| 3 | GROUP BY & Aggregation | `GROUP BY`, `SUM()`, `AVG()`, `AS` |
| 4 | Hybrid Workflow | Query Polars DataFrames directly — no import needed |
| 5 | Full Pipeline | DuckDB query → `.df()` → Plotly chart |

---

**Approach:** Every SQL concept is shown side-by-side with its Polars equivalent.
Zero SQL background needed — if you know Polars, you already know the logic.

**Stack:** Python 3.12 · DuckDB · Polars · Plotly · Rich · Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ali-datasmith/duckdb_sql_learning/blob/main/duckdb_sql_learning.ipynb)

---
## 🛠️ Tools & Environment

![Python](https://img.shields.io/badge/Python-3.12+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.26+-orange?logo=numpy)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-1.0+-blue?logo=polars)
![Plotly](https://img.shields.io/badge/Plotly-5.0+-3F4F75?logo=plotly)
![Rich](https://img.shields.io/badge/Rich-13.0+-2071B8?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-DuckDB%20Dialect-003B57?logo=sqlite&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-1.0+-FFBE00?logo=duckdb&logoColor=black)
---

## 🗺️ Learning Roadmap
```
Phase 01 ✅  Python + OOP          — Completed
Phase 02 ✅  Pandas + NumPy        — Completed (this repo)
Phase 03 ✅  Polars + Plotly       — Completed (this repo)
Phase 04 ✅ Rich                   — Completed (this repo)
Phase 05 ✅ DuckDB + SQL           — Completed (this repo)
Phase 06 ⏳  Streamlit             — Coming Soon
```

---

## 👤 Author

**Muhammad Ali Rajput**  
Python Developer | Aspiring Data Scientist  
[GitHub](https://github.com/Ali-datasmith)
