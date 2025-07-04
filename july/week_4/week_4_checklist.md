# ✅ WEEK 4 — Ultimate EDA Mini-Project Checklist

## 🎯 Goal

Use Python, Pandas, NumPy, Matplotlib & Seaborn together to perform a **complete Exploratory Data Analysis (EDA)**. Learn how to load data, clean it, analyze patterns, visualize findings & draw insights.

---

## 📌 1️⃣ Pick Dataset

- [ ] Choose a classic dataset:
  - Titanic (`titanic.csv`)
  - Iris (`iris.csv`)
  - Any Kaggle dataset (CSV)
- [ ] Save CSV to your `/Week4/` folder
- [ ] Load it with Pandas `pd.read_csv()`

---

## 📌 2️⃣ Inspect Data

- [ ] View top rows: `.head()`
- [ ] View bottom rows: `.tail()`
- [ ] Get shape: `.shape`
- [ ] Data types: `.dtypes`
- [ ] General info: `.info()`
- [ ] Summary stats: `.describe()`

✔️ _Mini:_ Note:

- How many rows/cols?
- Which columns are numerical? Categorical?

---

## 📌 3️⃣ Handle Missing Values

- [ ] Check missing values: `.isnull().sum()`
- [ ] Decide:
  - Drop rows? (`.dropna()`)
  - Fill with mean/median? (`.fillna()`)
  - Fill with mode? (`.fillna(value)`)

✔️ _Mini:_ Fix missing `Age` in Titanic with median.

---

## 📌 4️⃣ Clean Data

- [ ] Remove duplicate rows: `.drop_duplicates()`
- [ ] Rename columns if needed: `.rename()`
- [ ] Convert data types if needed: `.astype()`
- [ ] Create new columns (e.g., AgeGroup)

---

## 📌 5️⃣ Univariate Analysis

- [ ] Plot histogram for numerical columns
- [ ] Plot countplot for categorical columns
- [ ] Check outliers with boxplots

✔️ _Mini:_ Plot histogram for `Age` + boxplot for `Fare`.

---

## 📌 6️⃣ Bivariate Analysis

- [ ] Scatter plot: numerical vs numerical
- [ ] Boxplot: numerical vs categorical
- [ ] GroupBy: mean by category
- [ ] Correlation heatmap

✔️ _Mini:_ Boxplot of `Fare` vs `Pclass`.

---

## 📌 7️⃣ Categorical Analysis

- [ ] Countplot: `Sex`, `Embarked` (or other cat cols)
- [ ] Bar plot of survival by gender/class
- [ ] Pie chart for proportion of categories

---

## 📌 8️⃣ Feature Engineering

- [ ] Create new features: e.g., `FamilySize` in Titanic (`SibSp` + `Parch` + 1)
- [ ] Create bins/buckets: e.g., age groups (`pd.cut()`)

✔️ _Mini:_ Add `IsAlone` = 1 if no family.

---

## 📌 9️⃣ Insights

- [ ] Add markdown cell: summarize key findings
  - E.g., "Most survivors were women and children."
  - "Higher fare → higher survival chance."

---

## 📌 🔟 Save Clean Data

- [ ] Save cleaned dataset to new CSV: `.to_csv()`

---

## ✅ Deliverables

- [ ] Notebook: `week4_eda_project.ipynb`
- [ ] Dataset: in `/Week4/`
- [ ] Clear markdown sections:
  - Data Inspection
  - Cleaning
  - Univariate Plots
  - Bivariate Plots
  - Categorical Plots
  - Feature Engineering
  - Insights
- [ ] 8–10 plots minimum
- [ ] Export at least 1 plot as image
- [ ] Push cleaned CSV
- [ ] Push notebook to `/Week4/` on GitHub

---

## 🚀 Weekly Mission:

**Complete every tick → push → proudly share your first full EDA as proof you know real data work!**
