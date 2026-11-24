# 📊 Spread Locator — Statistical Distribution Analysis

**Discover the patterns behind transaction data using statistics, probability, and Python.**

Spread Locator is a data analysis project that explores how transaction amounts and transaction activity are distributed. It uses statistical distributions and data visualization techniques to understand transaction patterns, check normality, identify high-value transactions, and estimate probabilities.

## 🎯 Project Objectives

- Understand the distribution of transaction amounts.
- Analyze successful and failed transactions.
- Study weekly and daily transaction patterns.
- Identify high-value transactions using statistical techniques.
- Compare actual data with fitted probability distributions.
- Use statistical tests to understand the shape of the data.

## 🛠️ Tools & Technologies

- **Python** — Data analysis and calculations
- **Pandas & NumPy** — Data manipulation and numerical operations
- **Matplotlib & Seaborn** — Data visualization
- **SciPy** — Statistical distributions and hypothesis testing
- **Statsmodels** — Q-Q plot analysis
- **Jupyter Notebook** — Interactive analysis

## 🔍 Analysis Performed

| Analysis | Technique Used |
|---|---|
| Transaction success and failure | Probability & Bernoulli Distribution |
| Weekly transaction patterns | Binomial Distribution |
| Daily transaction frequency | Poisson Distribution |
| Transaction amount distribution | Log-Normal Distribution |
| High-value transaction analysis | Pareto Distribution |
| Normality checking | Shapiro-Wilk Test |
| Data transformation | Box-Cox Transformation |
| Unusual value analysis | Z-Score |
| Probability estimation | Log-Normal Survival Function |

## 📈 Key Features

- Analyzes transaction status and transaction amounts.
- Summarizes transaction activity by week and day.
- Visualizes actual transaction data against theoretical distributions.
- Checks whether transaction amounts follow a normal distribution.
- Applies Box-Cox transformation to study changes in data distribution.
- Compares estimated probability with the actual proportion of high-value transactions.

## 📂 Project Structure

```text
Spread-Locator/
├── Spread_Locator.ipynb
├── spread_locator_dataset.xlsx
└── README.md
```

## 🚀 How to Run

**Step 1:** Clone or download this repository from GitHub.

**Step 2:** Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels openpyxl jupyter
```

**Step 3:** Open the Jupyter Notebook.

```bash
jupyter notebook
```

**Step 4:** Open `Spread_Locator.ipynb` and run the cells in order.

**Important:** Keep `spread_locator_dataset.xlsx` in the same folder as the notebook. Update the dataset file path in the code if required.

## 💡 What I Learned

Through this project, I practiced statistical distribution analysis, probability calculations, data visualization, normality testing, data transformation, and interpreting patterns in real-world-style transaction data.

This project helped me understand how statistical concepts can be applied to explore data and support data-driven observations.

## 👩‍💻 Project Information

- **Project Name:** Spread Locator
- **Domain:** Data Analytics & Statistics
- **Project Type:** Jupyter Notebook Analysis
- **Focus:** Probability, Statistical Distributions & Data Visualization

---

⭐ If you find this project useful, feel free to explore the notebook and its analysis.
