<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,3,12,24&height=220&section=header&text=Descriptive%20Statistics&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=for%20Beginners%20%E2%80%94%20Python%20for%20Data%20Science&descAlignY=58&descSize=18" width="100%"/>

<br/>

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org)
[![Kaggle](https://img.shields.io/badge/Open%20on-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com)
[![License](https://img.shields.io/badge/License-MIT-ff6b6b?style=for-the-badge)](LICENSE)

<br/>

> *"You can't understand data you can't describe."*

**A colorful, beginner-friendly guide to describing any dataset with numbers and charts.** 📊

<br/>

</div>

---

## 📖 About

Imagine you have exam scores for 100 students. You can't read all 100 numbers and understand anything useful. **Descriptive statistics** lets you summarise that entire dataset into a handful of numbers — each one telling a different story.

This notebook walks you through every core measure from scratch, with plain-English analogies before every formula, hands-on code, and vibrant colorful visualizations. No prior statistics or math background needed.

---

## 🗺️ Table of Contents

- [What's Inside](#-whats-inside)
- [Quick Start](#-quick-start)
- [Requirements](#-requirements)
- [Cheat Sheet](#-cheat-sheet)
- [Practice Challenges](#-practice-challenges)
- [What's Next](#-whats-next)

---

## 📦 What's Inside

| # | Topic | What You'll Learn |
|---|-------|------------------|
| 1 | **Mean** | The average — and why outliers break it |
| 2 | **Median** | The middle value — resistant to outliers |
| 3 | **Mode** | Most frequent value — works on categories too |
| 4 | **Measures of Spread** | Range, variance, std deviation, IQR |
| 5 | **Percentiles & Quartiles** | Ranking values — Q1, Q2, Q3, ECDF |
| 6 | **Skewness & Kurtosis** | The shape of a distribution |
| 7 | **Full Workflow** | Everything together on a real multi-column DataFrame |

Every section uses the **same 60-student exam score dataset** so you see how each measure tells a different story about the same numbers.

---

## 🎨 Visual Highlights

```
📊  Histogram           — score distribution with mean & median lines
📦  Box plot            — IQR, quartiles, and outliers visualised
🎻  Violin plot         — distribution shape per subject
📈  ECDF curve          — cumulative percentile ranking
🌈  Quartile bar        — colourful Q1/Q2/Q3/Q4 breakdown
↔️  Std dev comparison  — same mean, three different spreads
↙↗  Skewness shapes    — right, symmetric, and left-skewed side by side
```

---

## ⚡ Quick Start

### Option 1 — Kaggle (Zero Setup)

[![Open on Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com)

1. Go to [kaggle.com/code](https://www.kaggle.com/code) → **New Notebook**
2. **File → Import Notebook** → upload `statistics_descriptive_stats.ipynb`
3. **Run All** ▶️ — all charts render instantly, no installs needed

### Option 2 — Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. **File → Upload notebook**
3. **Runtime → Run All**

### Option 3 — Run Locally

```bash
git clone https://github.com/nachiket-1/Know-Your-Data-Descriptive-Statistics-in-Python.git
cd descriptive-statistics-python
pip install -r requirements.txt
jupyter notebook know-your-data-descriptive-statistics-in-python.ipynb
```

---

## 📋 Requirements

```txt
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.5.0
scipy>=1.7.0
```

```bash
pip install -r requirements.txt
```

> ✅ All pre-installed on Kaggle and Google Colab.

---

## 📋 Cheat Sheet

| Measure | Code | When to use |
|---------|------|-------------|
| Mean | `np.mean(data)` | Symmetric data, no extreme outliers |
| Median | `np.median(data)` | Skewed data, income, house prices |
| Mode | `scipy.stats.mode(data)` | Categorical data, shoe sizes, votes |
| Std Dev | `np.std(data, ddof=1)` | Spread in original units |
| IQR | `np.percentile(d,75) - np.percentile(d,25)` | Spread without outlier influence |
| Percentile | `np.percentile(data, p)` | Ranking a value against others |
| Skewness | `pd.Series(data).skew()` | Checking distribution asymmetry |
| Full summary | `df.describe()` | First step on any new dataset |

---

## 🧪 Practice Challenges

After finishing the notebook, try these:

1. **Load the Titanic dataset** and run `.describe()` on `Age` and `Fare`
2. **Compare** mean vs median of `Fare` — which is more representative? Why?
3. **Find outliers** in `Age` using the 1.5×IQR rule
4. **Plot a violin plot** comparing `Fare` for survivors vs non-survivors
5. **Check skewness** of `Age` — does it match what you see in the histogram?

---

## 🚀 What's Next

| Topic | What you'll learn |
|-------|------------------|
| **Distributions** | Normal, binomial, Poisson — shapes of data |
| **Hypothesis Testing** | Is a result real or just random chance? |
| **Correlation** | How strongly do two variables move together? |
| **Regression** | Predict one variable from another |

---

## 🤝 Contributing

Found a bug or want to add a section?

1. Fork the repository
2. Create a branch: `git checkout -b feature/add-kurtosis-section`
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

Open source under the **MIT License**.

---

<div align="center">

**Made with ❤️, Python, and colorful charts**

If this helped you, drop a ⭐ on the repo!

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,3,12,24&height=120&section=footer" width="100%"/>

</div>
