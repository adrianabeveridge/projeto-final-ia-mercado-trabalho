# The Importance of AI in Our Lives and Work

### An Exploratory Analysis of the Impact of Artificial Intelligence on the Global Labor Market (2020–2026)

**Final Project — Data Analyst**
**Author:** Adriana Beveridge · adriana.beveridge@gmail.com

---

## 📋 About the Project

Artificial Intelligence is no longer a futuristic promise — it has become part of everyday professional life. But the real impact varies a lot, depending on occupation, industry, and country. This project uses data to investigate, with evidence, how this transformation is happening.

## ❓ Research Questions

1. Which occupations and industries are most at risk of being replaced by AI?
2. Is AI adoption related to salary increases or decreases?
3. How has automation risk evolved from 2020 to 2026?
4. Is there a difference between countries in AI adoption level and salary impact?
5. Which occupations have the greatest reskilling urgency?

As a bonus, the project also builds an **AI Vulnerability Index (AIVI)** — a custom metric created by combining automation risk, reskilling urgency, and AI disruption intensity with weighted scoring.

## 🔑 Key Findings

- 🚚 **Truck Driver (60.7%)** and **Customer Support Rep (59.9%)** have the highest automation risk; **Software Engineer (34.9%)** and **Data Analyst (35.5%)** have the lowest.
- 💰 The correlation between AI adoption and salary change is **essentially null (r ≈ 0.000)** — adopting more AI was not associated with earning more or less, in this dataset.
- 📈 Automation risk stayed **stable overall (2020–2026)**, but with opposite trajectories by sector: Technology decreased (-2.5 p.p.), Retail and Energy increased (+3.0 and +2.0 p.p.).
- 🌎 **Brazil is at the group average** among countries, both in AI adoption and salary change (-0.06%, stable).
- 🎯 The **AI Vulnerability Index** confirms: Truck Driver (100/100) is the most vulnerable occupation; Software Engineer (0.3/100) is the safest.

## 📊 Dataset

[**Future of Work in the Age of AI (2020–2026)**](https://www.kaggle.com/datasets/algozee/future-of-work-in-the-age-of-ai-20202026) — Kaggle

A synthetic dataset with 15,000 records, covering 8 industries, 9 countries, and 10 job roles, with metrics on automation risk, AI adoption, salary change, reskilling urgency, and disruption intensity.

## 🗂️ Repository Structure

```
├── Final_Project_AI_Impact_on_Work.ipynb     # Notebook with the full analysis (Python)
├── ai_job_replacement_2020_2026_v2.csv       # Dataset used
├── Projeto_Final_Apresentacao.pdf            # Slide presentation
└── README.md                                 # This file
```

## 🛠️ Tools Used

- **Python** — pandas, numpy, scikit-learn
- **Visualization** — matplotlib, seaborn, plotly
- **Jupyter Notebook**

## 🚀 How to Run the Notebook

1. Clone this repository or download the files
2. Make sure `ai_job_replacement_2020_2026_v2.csv` is in the same folder as the notebook
3. Install the dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
   ```
4. Open the notebook in Jupyter and run all cells (`Kernel → Restart & Run All`)

## 📌 Limitations

- The dataset is synthetic (generated for educational purposes); absolute values do not represent official market statistics.
- The analysis is correlational, not causal.
- The AI Vulnerability Index is an original construct of this project, with weights defined by reasonable judgment.

---

*Project developed as part of the Data Analyst program.*
