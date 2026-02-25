# A Structured Framework for Selecting Indian Equity Mutual Funds  
### A Quantitative–Qualitative Scoring Approach for Long-Term Investors  

**Author:** George Elias  
**Affiliation:** Master’s Student, International Finance  
**Project Type:** Independent Research  
**Disclaimer:** This project is for educational and analytical purposes only and does not constitute investment advice.

---

## Overview

This project develops and implements a structured framework to evaluate and rank Indian equity mutual funds using a combination of quantitative metrics and qualitative assessment.

Rather than relying solely on headline past returns, the framework emphasizes:

- Risk-adjusted performance  
- Downside protection  
- Performance consistency across market cycles  
- Fund manager stability  
- Organizational robustness  
- Cost efficiency and investor suitability  

The objective is to replicate the analytical workflow of a junior buy-side analyst systematically screening funds for long-term investors.

---

## Research Objectives

1. Design a transparent and repeatable scoring model for equity mutual fund evaluation  
2. Apply the framework to a representative universe of Indian equity funds  
3. Test the robustness of rankings under varying weight assumptions  
4. Assess the strengths and limitations of a rules-based fund selection approach  

---

## Fund Universe

### Categories Analyzed
- Large Cap  
- Flexi Cap  
- Mid Cap  

### Exclusion Criteria
- Funds with less than 5 years of NAV history  
- Funds with mandate or benchmark changes during the analysis period  
- Funds with incomplete publicly available data  

Final universe: ~100 Indian equity mutual funds.

Funds are ranked **within category**, not across categories.

---

## Framework Structure

Funds are evaluated across six weighted pillars:

| Pillar | Weight |
|--------|--------|
| Performance | 25% |
| Risk Management | 25% |
| Consistency | 15% |
| Fund Manager Quality | 15% |
| Organization Quality | 10% |
| Costs & Product Fit | 10% |

The framework prioritizes risk control and consistency over pure return maximization.

---

## Quantitative Metrics

### Performance
- 3-Year CAGR  
- 5-Year CAGR  

### Risk
- Standard Deviation (3Y)  
- Maximum Drawdown (3Y)  

### Consistency
- Rolling 12-month outperformance frequency  
- Worst rolling 1-year return  

### Cost & Structure
- Expense Ratio  
- AUM considerations  

All metrics are normalized using min–max scaling within each category.  
Metrics where lower values are preferable are inverted before aggregation.

Each fund receives:
- Sub-metric scores  
- Pillar-level scores  
- Composite score (0–100)  

---

## Qualitative Overlay

Quantitative screening is complemented with:

- Fund manager tenure analysis  
- Management continuity assessment  
- AMC scale and governance review  
- Style drift evaluation  
- Portfolio concentration and scalability considerations  

This ensures decisions are not based solely on statistical outputs.

---

## Tools & Implementation

- **Python (Pandas, NumPy)** – Data cleaning, metric computation, normalization  
- **Excel** – Cross-validation and data verification  
- **Power BI** – Interactive dashboard visualization  
- Publicly available NAV and fund-level datasets  

The project emphasizes reproducibility, clarity, and structured decision-making.

---

## Key Findings

- Top-ranked funds were not necessarily the highest-return funds  
- Consistency and downside control significantly influenced rankings  
- Rankings remained broadly stable under ±10% weight adjustments  
- Simplified historical testing suggested improved drawdown characteristics versus category averages  

The framework appears conservative and risk-aware by design.

---

## Limitations

- Survivorship bias in available datasets  
- Fully backward-looking metrics  
- Subjectivity in qualitative scoring  
- Simplified backtesting assumptions  
- Limited portfolio-level factor exposure analysis  

These constraints are acknowledged to avoid overstating conclusions.

---

## Future Enhancements

- Factor attribution (value, momentum, quality exposure)  
- Automated periodic re-ranking system  
- Investor-specific risk customization module  
- Extension to hybrid and international funds  
- Advanced risk decomposition and beta stability testing  

---

## Project Philosophy

This project demonstrates structured analytical thinking, risk-aware investment evaluation, and transparent documentation of assumptions.  

It reflects how disciplined capital allocation decisions can be systematized at scale using both quantitative rigor and qualitative judgment.
