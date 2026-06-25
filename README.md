 # AI Risk Analysis Dashboard

An exploratory data analysis (EDA) project examining AI-related risk incidents using the **MIT AI Risk Repository** — one of the most comprehensive academic databases of real-world AI failures, harms, and near-misses.

> 📊 Dataset source: [MIT AI Risk Repository](https://airisk.mit.edu/blog/repository-update-december-2025)

---

## Project Overview

This project analyzes patterns in AI risk incidents to answer key questions:

- What **types of AI risk** are most prevalent — technical failures, misuse, or unintended consequences?
- What is the **severity and impact level** distribution across reported incidents?
- How do **human-caused vs AI-caused** incidents differ in frequency, severity, and domain?

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core analysis language |
| **pandas** | Data loading, cleaning, and transformation |
| **matplotlib** | Static visualizations and chart exports |
| **seaborn** | Statistical visualizations and heatmaps |
| **Jupyter Notebook** | Interactive analysis environment |

---

## Key Analysis Areas

**1. Risk Category Breakdown**
Classified incidents by risk type — identifying which categories (e.g. bias/fairness, safety failures, privacy violations, misinformation) appear most frequently in the dataset.

**2. Severity & Impact Analysis**
Examined the distribution of incident severity levels — from minor harms to critical failures — and identified which risk categories tend to produce the most severe outcomes.

**3. Human vs AI Causation**
Compared incidents where human decisions were the primary cause vs those where AI system behavior was the driver — analysing how causation patterns vary across domains and severity levels.

---

## Key Findings
 
- The most frequently reported risk categories are human with intentional behavior and AI-based with unintended behavior
- Incidents are reported with the source of systematic risks from general-purpose AI  
- Human-caused incidents outnumber purely AI-caused ones, highlighting that deployment decisions and oversight gaps remain the primary risk driver

---

## Project Structure

```
AI-Risk-analysis/
├── ai-risk-analysis.ipynb    # Main analysis notebook
└── README.md
```

---


---

## Dataset

The **MIT AI Risk Repository** is maintained by MIT FutureTech and contains hundreds of real-world AI incident records categorized by risk type, domain, severity, geography, and causal factors. It is one of the most rigorous publicly available datasets for AI safety and risk research.

---

