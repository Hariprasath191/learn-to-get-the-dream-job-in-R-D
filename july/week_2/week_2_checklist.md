# ✅ WEEK 2 — Ultimate NumPy & Pandas Foundations Checklist

## 🎯 Goal
Understand how to work with **NumPy arrays** and **Pandas DataFrames** — the two core tools for real data science and ML workflows.

---

## 📌 1️⃣ NumPy Basics

- [ ] Install NumPy (`pip install numpy`)
- [ ] Import NumPy (`import numpy as np`)
- [ ] Understand difference: Python lists vs NumPy arrays

---

## 📌 2️⃣ Creating Arrays

- [ ] Create 1D array: `np.array([1, 2, 3])`
- [ ] Create 2D array: `np.array([[1,2],[3,4]])`
- [ ] Use `np.arange()`, `np.linspace()`
- [ ] Create zeros & ones: `np.zeros()`, `np.ones()`
- [ ] Create identity matrix: `np.eye()`
- [ ] Random numbers: `np.random.rand()`, `np.random.randn()`, `np.random.randint()`

---

## 📌 3️⃣ Array Properties

- [ ] `.shape`  
- [ ] `.dtype`  
- [ ] `.ndim`  
- [ ] `.size`  

✔️ *Mini:* Make an array → check all properties.

---

## 📌 4️⃣ Indexing & Slicing

- [ ] Index single elements
- [ ] Slice rows, columns in 2D arrays
- [ ] Boolean indexing (`arr[arr > 5]`)
- [ ] Fancy indexing (array of indices)

✔️ *Mini:* Replace values conditionally: `arr[arr < 0] = 0`

---

## 📌 5️⃣ Array Operations

- [ ] Arithmetic operations (`+`, `-`, `*`, `/`)
- [ ] Element-wise vs matrix multiplication
- [ ] Use `np.sum()`, `np.mean()`, `np.std()`, `np.min()`, `np.max()`
- [ ] Axis parameter: sum along rows vs columns

✔️ *Mini:* Make 2 arrays → add, subtract, multiply, divide.

---

## 📌 6️⃣ Reshape & Resize

- [ ] `.reshape()`
- [ ] `.flatten()`
- [ ] `.ravel()`
- [ ] Transpose: `.T`

✔️ *Mini:* Reshape (1,10) → (2,5).

---

## 📌 7️⃣ Pandas Basics

- [ ] Install Pandas (`pip install pandas`)
- [ ] Import Pandas (`import pandas as pd`)
- [ ] Understand Series vs DataFrame

---

## 📌 8️⃣ Creating Series

- [ ] From list
- [ ] From dictionary
- [ ] Specify index & name

✔️ *Mini:* Create Series with custom index.

---

## 📌 9️⃣ Creating DataFrame

- [ ] From dictionary of lists
- [ ] From list of dicts
- [ ] From CSV

✔️ *Mini:* Create a small DataFrame manually.

---

## 📌 🔟 Reading Data

- [ ] `pd.read_csv()`
- [ ] `pd.read_excel()` (optional)
- [ ] Check `.head()`, `.tail()`
- [ ] `.info()`, `.describe()`

---

## 📌 1️⃣1️⃣ Exploring Data

- [ ] Access columns: `df['col']`
- [ ] Add new column
- [ ] Delete column: `del` or `.drop()`
- [ ] Filter rows by condition
- [ ] Multiple conditions (`&` and `|`)

✔️ *Mini:* Filter Titanic rows: `Age > 30`, `Sex == 'female'`.

---

## 📌 1️⃣2️⃣ Indexing & Slicing

- [ ] `.loc[]` — label-based indexing
- [ ] `.iloc[]` — position-based indexing
- [ ] `.at[]`, `.iat[]` — fast single value access
- [ ] Set index: `.set_index()`
- [ ] Reset index: `.reset_index()`

✔️ *Mini:* Use `.loc[]` to get specific rows & columns.

---

## 📌 1️⃣3️⃣ Handling Missing Data

- [ ] `.isnull()`, `.notnull()`
- [ ] `.dropna()`
- [ ] `.fillna()`

✔️ *Mini:* Fill missing Age with mean Age.

---

## 📌 1️⃣4️⃣ Basic GroupBy

- [ ] `df.groupby('col').mean()`
- [ ] Count rows per group
- [ ] Aggregate multiple functions

✔️ *Mini:* Group Titanic by `Sex` and get average `Fare`.

---

## 📌 1️⃣5️⃣ Basic Sorting

- [ ] `.sort_values()`
- [ ] `.sort_index()`

✔️ *Mini:* Sort Titanic by `Fare`.

---

## 📌 1️⃣6️⃣ Exporting Data

- [ ] `.to_csv()`
- [ ] `.to_excel()`

✔️ *Mini:* Save a cleaned DataFrame to new CSV.

---

## ✅ Deliverables

- [ ] Notebook: `week2_numpy_pandas.ipynb`
- [ ] Each section with examples & markdown explanations
- [ ] One simple dataset (Titanic, Iris, or sample CSV)
- [ ] Pushed to `/Week2/` folder on GitHub

---

## 🚀 Weekly Mission: **Finish every tick → push → level up your data handling confidence!**
