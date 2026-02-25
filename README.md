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
- Performance consistency across market cycles  
- Organizational robustness  
- Cost efficiency and investor suitability  



## Research Objectives

1. Design a transparent and repeatable scoring model for equity mutual fund evaluation  
2. Apply the framework to a representative universe of Indian equity funds  
3. Assess the strengths and limitations of a rules-based fund selection approach  



## Fund Universe

### Categories Analyzed 
- Flexi Cap  

### Exclusion Criteria
- Funds with less than 5 years of NAV history  
- Funds with mandate or benchmark changes during the analysis period  
- Funds with incomplete publicly available data

Funds are ranked **within category**, not across categories.

---

## Framework Structure

Funds are evaluated across six weighted pillars:

| Pillar | Weight |
|--------|--------|
| Performance & Consistency | 25% |
| Risk Management | 25% |
| Consistency | 15% |
| Management & Organization Quality | 10% |
| Costs | 10% |

The framework prioritizes risk control and consistency over pure return maximization.



## Tools & Implementation

- **Python (Pandas, NumPy)** – Data cleaning, metric computation, normalization  
- **Excel** – Scoring analysis and data verification
- **Word** - Insights documentation
- Publicly available NAV and fund-level datasets from Morningstar, Value Research, NSE, and Kaggle

The project emphasizes reproducibility, clarity, and structured decision-making.

---

## Key Findings

- Top-ranked funds were not necessarily the highest-return funds  
- Consistency and downside control significantly influenced rankings

The framework appears conservative and risk-aware by design.

---

## Limitations

- Survivorship bias in available datasets  
- Entirely backward-looking metrics  
- Subjectivity in qualitative scoring  
- Simplified backtesting assumptions 

These constraints are acknowledged to avoid overstating conclusions.

---

## Future Enhancements

- Factor attribution (market, value, momentum, quality exposure)  
- Automated periodic re-ranking system  
- Investor-specific risk customization module  
- Extension to hybrid and international funds  
- Advanced risk decomposition and beta stability testing  

---

## Project Philosophy

This project demonstrates structured analytical thinking, risk-aware investment evaluation, and transparent documentation of assumptions.  

It reflects how disciplined capital allocation decisions can be systematized at scale using both quantitative rigor and qualitative judgment.
