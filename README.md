 # AI Risk Analysis Dashboard

An exploratory data analysis (EDA) project examining AI-related risk incidents using the **MIT AI Risk Repository** — one of the most comprehensive academic databases of real-world AI failures, harms, and near-misses.

> 📊 Dataset source: [MIT AI Risk Repository](https://airisk.mit.edu/blog/repository-update-december-2025)

---

## Project Overview

This project analyzes patterns in AI risk incidents to answer key questions:

- What **types of AI risk** are most prevalent — technical failures, misuse, or unintended consequences?
- How have AI risk incidents **trended over time** — are they increasing, decreasing, or shifting in nature?
- Which **countries and regions** are most affected by or responsible for AI-related harms?
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

**2. Trend Analysis Over Time**
Tracked year-over-year changes in reported AI risk incidents — visualizing whether specific risk types are growing faster than others and identifying inflection points.

**3. Geographic Distribution**
Mapped incidents by country and region — identifying which parts of the world generate the most AI risk reports and whether risk profiles differ by geography.

**4. Severity & Impact Analysis**
Examined the distribution of incident severity levels — from minor harms to critical failures — and identified which risk categories tend to produce the most severe outcomes.

**5. Human vs AI Causation**
Compared incidents where human decisions were the primary cause vs those where AI system behavior was the driver — analysing how causation patterns vary across domains and severity levels.

---

## Key Findings

- AI risk incidents have grown significantly year-over-year, with the sharpest increases in recent years
- The most frequently reported risk categories are centered around misuse, bias, and unintended system behavior
- Incidents are concentrated in a small number of high-income countries, reflecting both higher AI adoption and stronger reporting infrastructure
- High-severity incidents are disproportionately associated with specific domains (e.g. healthcare, autonomous systems, criminal justice)
- Human-caused incidents outnumber purely AI-caused ones, highlighting that deployment decisions and oversight gaps remain the primary risk driver

---

## Project Structure

```
AI-Risk-analysis/
├── ai-risk-analysis.ipynb    # Main analysis notebook
└── README.md
```

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/thienTrungSon/AI-Risk-analysis.git
   cd AI-Risk-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. Download the dataset from the [MIT AI Risk Repository](https://airisk.mit.edu/blog/repository-update-december-2025) and place it in the project folder.

4. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook ai-risk-analysis.ipynb
   ```

---

## Dataset

The **MIT AI Risk Repository** is maintained by MIT FutureTech and contains hundreds of real-world AI incident records categorized by risk type, domain, severity, geography, and causal factors. It is one of the most rigorous publicly available datasets for AI safety and risk research.

---

