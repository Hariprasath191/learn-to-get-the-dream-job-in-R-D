# ✅ WEEK 3 — Ultimate Data Visualization Checklist (Matplotlib & Seaborn)

## 🎯 Goal
Master **Matplotlib** and **Seaborn** for beautiful, clear, and professional plots. Learn how to customize charts, handle real data, and tell compelling visual stories.

---

## 📌 1️⃣ Install & Import

- [ ] Install Matplotlib: `pip install matplotlib`
- [ ] Install Seaborn: `pip install seaborn`
- [ ] Import:
  ```python
  import matplotlib.pyplot as plt
  import seaborn as sns
## 📌 2️⃣ Matplotlib Basics
 Create simple line plot with plt.plot()

 Plot multiple lines on one chart

 Add chart title, X and Y axis labels

 Add legend for multiple lines

 Customize line color, style, marker

✔️ Mini-Task: Plot y = x and y = x^2 on same chart.

## 📌3️⃣ Scatter Plots
 Create scatter plot with plt.scatter()

 Change point color and size

 Add grid for better readability

✔️ Mini-Task: Scatter plot: Titanic Age vs Fare.

📌 4️⃣ Bar Plots
 Create vertical bar chart with plt.bar()

 Create horizontal bar chart with plt.barh()

 Add value labels to bars

 Customize bar colors, width

✔️ Mini-Task: Bar chart for Titanic survival count by gender.

📌 5️⃣ Histograms
 Plot histogram with plt.hist()

 Use bins, set edgecolor for clarity

 Overlay multiple histograms

✔️ Mini-Task: Histogram for age distribution.

📌 6️⃣ Pie Charts
 Create pie chart with plt.pie()

 Add labels and percentages

 Use explode for slice emphasis

✔️ Mini-Task: Pie chart for class proportion (1st, 2nd, 3rd).

## 📌 7️⃣ Subplots
 Use plt.subplot() for multiple plots in one figure

 Use plt.subplots() for flexible layout

 Adjust figure size and spacing

✔️ Mini-Task: Line plot + bar plot side by side.

## 📌 8️⃣ Save Figures
 Save figure as PNG: plt.savefig('plot.png')

 Save figure as PDF or other formats

## 📌 9️⃣ Seaborn Basics
 Understand Seaborn vs Matplotlib

 Use sns.set_style() to change plot theme

 Use Seaborn color palettes

## 📌 🔟 Seaborn Plots
 sns.histplot() — histogram with KDE option

 sns.boxplot() — visualize distribution and outliers

 sns.violinplot() — variation of boxplot

 sns.scatterplot() — scatter plot with hue for categories

 sns.lineplot() — line plots with confidence intervals

✔️ Mini-Task: Boxplot: Fare by Passenger Class (Titanic).

## 📌 1️⃣1️⃣ Categorical Plots
 sns.countplot() — count of categories

 sns.barplot() — bar plot with mean aggregation

 sns.catplot() — flexible categorical plot

✔️ Mini-Task: Countplot of survived vs not survived.

## 📌 1️⃣2️⃣ Pairplots & Heatmaps
 sns.pairplot() — scatterplot matrix for relationships

 sns.heatmap() — show correlation matrix visually

✔️ Mini-Task: Heatmap of correlation matrix for Titanic data.

## 📌 1️⃣3️⃣ Customizing Seaborn
 Add title, axis labels, and legend

 Change color palette (dark, pastel, muted, etc.)

 Switch between whitegrid, darkgrid styles

## 📌 1️⃣4️⃣ Inline vs Save
 Use %matplotlib inline for Jupyter

 Export final plots as images for reports

✅ Deliverables
 Notebook: week3_visualization.ipynb

 Sections: Matplotlib basics, Seaborn basics, practical plots

 Use real dataset (Titanic, Iris, or any CSV)

 Minimum 8–10 plots, each well commented

 Save at least one plot as PNG

 Push to /Week3/ folder on GitHub