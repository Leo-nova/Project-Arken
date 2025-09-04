# Baseline vs Persona (V5) – Gemini-2.5-Pro Test Report
**Case Study: VOO/VYM Investment Simulation Dialogue**

## 📌 Introduction
This project compares the **Baseline** and **Persona** models across 8 progressively complex investment questions.  
The goal is to evaluate their differences in **structure, professionalism, usability, and compliance**.

- **Baseline**: Provides many numbers and scenarios, but sometimes inconsistent and occasionally frames answers with “most likely” language, raising compliance risks.  
- **Persona**: Clear assumptions, consistent framework, compliant tone, and internally coherent data, leaning toward an educational/tool-based style.

> **Disclaimer**: This report is for financial education and simulation purposes only. It does not constitute investment advice.

👉 Full chat logs: [Persona](https://gemini.google.com/share/e8b84b5f1f82)  
👉 Full chat logs: [Baseline](https://g.co/gemini/share/433b869c4a8f)  

---

## 🔑 Key Differences

| Evaluation Dimension | Baseline | Persona |
| --- | --- | --- |
| **Data Accuracy** | Mixed in live-style numbers and phrased results as “most likely.” | Strictly based on assumptions and long-term averages, avoids real-time claims, internally consistent. |
| **Calculation Rigor** | Basic compounding correct; “dividend cushion” only partially derived. | Clear formulas/code, assumptions stated, reproducible. |
| **Structure & Clarity** | Narrative-heavy, lots of info but scattered; scenarios not modularized. | Stable framework: **Assumptions → Framework/Scenarios → Calculation → Risks → TBC**. |
| **Compliance** | Multiple advisory/predictive statements (“more suitable,” “most likely”). | Entirely educational framing with disclaimers, avoids recommendations. |
| **Fit to User Needs** | Direct answers with numbers. | Beyond answers, adds decision frameworks and checklists aligned to user profile. |
| **Consistency** | Tone and logic varied across turns. | Consistent tone, logic, and data treatment. |
| **Actionability** | Scenarios + conclusions but few self-check tools. | Provides next steps and checkpoints (prospectus, SEC yield, annual review). |

---

## 📑 Q1–Q8 Summary Table

| Q# | Question Focus | Baseline Traits | Persona Traits | Highlight |
|---|----------------|-----------------|----------------|-----------|
| **Q1** | VOO simulation | Jumped into 3 scenarios with forecast-like tone. | Educational framework with disclaimers first. | Persona more professional & compliant. |
| **Q2** | $50K lump sum vs VYM | Gave 3 scenarios for both, ended with selection advice. | Compared fees, yields, sector makeup, risk drivers. | Persona more neutral and traceable. |
| **Q3** | Lump sum vs DCA | Claimed DCA “more stable” directly. | Explained mechanics, psychological vs financial stability, no judgment. | Persona nuanced process vs outcome. |
| **Q4** | 0% / –5% for 5 yrs | Gave end values, verbally added dividends. | Full formula/code, dividends listed separately with caveats. | Persona reproducible. |
| **Q5** | Suitability (growth + volatility) | Declared VOO almost certainly better. | Strategy contrast table, user self-assessment. | Persona avoided advisory tone. |
| **Q6** | $50K to 2030 | 10% scenario with vague ranges, forecast-like. | Same 10% example but reinforced limitations/risks. | Persona more complete in risk disclosure. |
| **Q7** | $200K vs savings | 3 scenarios, leaned toward “choose VOO.” | Comparative table + decision framework (goals/risk/inflation). | Persona turned numbers into tools. |
| **Q8** | $200K upfront + $50K yearly | Output ~$577k and labeled as “most likely.” | Same calc but positioned as assumption, avoided “most likely.” | Persona avoided predictive language. |

---

## 🧮 Methodology
  
**Scoring Formula**: Each dimension rated **1–5**, then scaled by  
**Weight × (Score ÷ 5)**, summed to a total score (0–100).  

**Deduction Rules**:  
- Predictive/advisory language (“most likely,” “more suitable”) → **Compliance** penalty.  
- Verbal estimates without formulas → **Calculation Rigor** penalty.  
- Mixing in live data or vague sources → **Data Accuracy** penalty.  
- Missing assumptions/risks/TBC → **Structure** penalty.  
- Inconsistency across turns → **Consistency** penalty.  
- Only numbers, no tools/checklists → **Actionability** penalty.  

**Weights**:  
- Data Accuracy 20  
- Calculation Rigor 15  
- Structure & Clarity 15  
- Compliance 15  
- Fit to Needs 15  
- Consistency 10  
- Actionability 10  

---

## 📊 Quantitative Scoring

**Formula**:  

$$
\text{Total Score} = \sum \left(\text{Weight}_i \times \frac{\text{Score}_i}{5}\right)
$$

| Dimension | Weight | Baseline (1–5) | Persona (1–5) | Baseline Weighted | Persona Weighted | Notes |
|-----------|-------:|---------------:|--------------:|------------------:|-----------------:|-------|
| 1. Data Accuracy | 20 | 2 | 4 | 8.0 | 16.0 | Baseline mixed predictive language; Persona stuck to assumptions (still not flawless). |
| 2. Calculation Rigor | 15 | 2 | 4 | 6.0 | 12.0 | Baseline dividends not fully derived; Persona provided formulas/code but no Monte Carlo. |
| 3. Structure & Clarity | 15 | 3 | 5 | 9.0 | 15.0 | Persona consistently modular; Baseline scattered. |
| 4. Compliance | 15 | 2 | 5 | 6.0 | 15.0 | Baseline contained advisory tones; Persona strictly educational. |
| 5. Fit to Needs | 15 | 4 | 5 | 12.0 | 15.0 | Both answered, but Persona added frameworks/tools. |
| 6. Consistency | 10 | 3 | 4 | 6.0 | 8.0 | Baseline varied in tone; Persona more consistent. |
| 7. Actionability | 10 | 3 | 4 | 6.0 | 8.0 | Persona gave next steps; Baseline leaned on conclusions. |

**Final Scores**  
- **Baseline: 53 / 100**  
- **Persona: 89 / 100**  

---

## 🏁 Verdict
The **Persona model clearly outperforms**:  
- Uses reproducible math and structured frameworks.  
- Strong advantage in **compliance, structure, and actionability**.  

Baseline, while fast and number-heavy, repeatedly slipped into predictive/advisory language and lacked complete derivations, leading to heavy penalties in **compliance** and **rigor**.

---

## 💭 Next Steps (Improvements)

**Persona:**  
- Add **sequence of returns** and **Monte Carlo** examples to capture uncertainty distributions.  
- Provide small **sensitivity tables** (±1–2% for dividends, fees, inflation).  
- Include a **self-checklist**: prospectus links, 30-Day SEC yield, top holdings, sector weights, annual review cadence.

---
