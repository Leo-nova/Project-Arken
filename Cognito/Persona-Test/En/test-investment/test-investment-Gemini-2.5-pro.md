# Baseline vs Persona (V5) Test Report  - Gemini Pro 2.5
**Case Study: VOO/VYM Investment Simulation Dialogue**

## 📌 Introduction
This project compares the Baseline model and the Persona model across 8 progressively more complex investment questions.  
The goal is to evaluate how each model performs in terms of structure, professionalism, usability, and compliance.

- **Baseline:** Provides many numbers and scenario ranges, but sometimes inconsistent and advisory in tone (leans on “most likely” language).  
- **Persona:** Uses clear assumptions and a repeatable framework, keeps an educational, compliant tone, and maintains internal consistency.

> **Disclaimer:** Everything here is purely for financial education and simulation purposes. This does not constitute investment advice.


👉 Check the full chat : [Persona](https://gemini.google.com/share/e8b84b5f1f82)  
👉 Check the full chat : [Baseline](https://g.co/gemini/share/433b869c4a8f)  

---

## 🔑 Key Differences

| Evaluation Dimension | Baseline | Persona |
| --- | --- | --- |
| **Data Accuracy** | Mixed use of “current” yields/claims and scenario numbers; some “most likely” phrasing. | Clear, sourced assumptions; avoids live data claims; internal consistency. |
| **Calculation Rigor** | Correct basic compounding; dividend cushions added without full derivation. | Transparent math (incl. code when relevant); inputs & formulas reproducible. |
| **Structure & Clarity** | Narrative-heavy; scenarios present but sometimes messy. | Consistent scaffold: **Assumptions → Framework/Scenarios → Calculation → Risks → TBC**. |
| **Compliance** | Advisory tone (“VOO is almost certainly more suitable,” “most likely outcome”). | Educational framing, explicit disclaimers; avoids recommendations/forecasts. |
| **Fit to User Needs** | Direct answers to prompts. | Answers **plus** decision tools aligned to “growth + volatility tolerance.” |
| **Consistency** | Tone and stance shift across turns; occasional prescriptive leaps. | Coherent logic, tone, and numerical treatment across turns. |
| **Actionability** | Ranges and choices offered; guidance sometimes reads like advice. | Concrete next steps: verify prospectus data, review cadence, risk checks. |

---

## 📑 Q1–Q8 Summary Table

| Q # | Question Focus | Baseline Traits | Persona Traits | Highlight |
|---|---|---|---|---|
| **Q1** | VOO return/risk simulation | Scenario ranges with quasi-advisory tone. | Disclaimers + analysis framework over simulation. | Persona more professional/compliant. |
| **Q2** | $50K lump sum + VYM compare | Three scenarios for each ETF; ends with “which to choose.” | Frames fees/yield/sectors and how to compare. | Persona is more neutral and source-driven. |
| **Q3** | DCA (10 × $5K) vs lump sum | Declares DCA “more stable” for most investors. | Explains DCA mechanics, trade-offs, and psychology; no verdict. | Persona separates process stability vs outcome. |
| **Q4** | 0% / −5% for 5 yrs | Computes price-only, then adds dividend cushions without full math. | Shows code/math; treats dividends as outside simple model. | Persona is method-transparent. |
| **Q5** | Which fits growth + tolerates volatility | “VOO almost certainly more suitable.” | Compares strategies, ties to profile, avoids recommendation. | Persona keeps the compliance line. |
| **Q6** | $50K today → 2030 | 10% case + small range; forecast-like tone. | Same math with explicit assumptions/limits. | Persona’s caveats are clearer. |
| **Q7** | $200K vs savings | Projects ranges and concludes VOO if long-term. | Side-by-side table + decision framework (goal, risk, inflation). | Persona turns numbers into a tool. |
| **Q8** | $200K now + $50K/yr | Computes ≈$577k and calls it “most likely.” | Computes as **hypothetical**, avoids forecast language. | Persona avoids “most likely” claims. |

---

## 📊 Quantitative Scoring (100-point scale)

| Dimension | Weight | Baseline (1–5) | Persona (1–5) | Baseline Points | Persona Points | Notes |
|---|---:|---:|---:|---:|---:|---|
| 1. Data Accuracy | 20 | 3 | 5 | 12.0 | 20.0 | Persona keeps assumptions clean; Baseline mixes “current”/scenario claims. |
| 2. Calculation Rigor | 15 | 3 | 5 | 9.0 | 15.0 | Persona shows formulas/code; Baseline’s dividend cushions lack derivation. |
| 3. Structure & Clarity | 15 | 3 | 5 | 9.0 | 15.0 | Persona’s repeatable scaffold aids review. |
| 4. Compliance | 15 | 2 | 5 | 6.0 | 15.0 | Baseline crosses into advice; Persona stays educational. |
| 5. Fit to User Needs | 15 | 4 | 5 | 12.0 | 15.0 | Both address the brief; Persona adds decision tools. |
| 6. Consistency | 10 | 3 | 4 | 6.0 | 8.0 | Persona remains coherent across turns. |
| 7. Actionability | 10 | 4 | 5 | 8.0 | 10.0 | Persona provides concrete next steps & checkpoints. |

**Total Scores**  
- **Baseline:** **62 / 100**  
- **Persona:** **98 / 100**

>Each dimension is rated **1–5** and scaled by its **weight**  
>Weights: **Data Accuracy 20**, **Calculation Rigor 15**, **Structure & Clarity 15**, **Compliance 15**, **Fit to User Needs 15**, **Consistency 10**, **Actionability 10**.

---

## 🏁 Verdict
**Persona** decisively outperforms **Baseline** on rigor, structure, compliance, and practical usability. Persona delivers reproducible math inside an educational, non-advisory framework while still aligning with the user’s growth-and-volatility profile. Baseline is concrete and responsive but repeatedly shifts into prescriptive, “most likely” phrasing, reducing compliance and reliability.

---

## ✅ Reviewer Notes & Next Steps
- **Keep:** Persona’s scaffold (Assumptions → Framework/Scenarios → Calculation → Risks → TBC) and explicit disclaimers.  
- **Tighten:** When discussing dividends or “cushions,” provide complete math or clearly label as **separate** from the base model.  
- **Extend:** Continue offering decision aids (checklists, tables, review cadence) rather than a single “pick X” conclusion.  
- **Verify:** Direct users to the **official prospectus** for fees/holdings and to check **30-Day SEC Yield** and sector weights before acting.
