# Day 16 - Claude Custom Skill: Stock Fundamental Research

## Objective

Built a custom Claude Skill called **stock-fundamental-research** to automate fundamental analysis of Indian and global listed companies. The goal was to create a reusable research assistant capable of generating structured stock analysis reports using financial metrics, valuation indicators, ownership trends, business quality assessment, competitive positioning, and risk analysis.

---

## What I Built

### Skill Name

stock-fundamental-research

### Purpose

The skill analyzes publicly listed companies using fundamental analysis principles and generates evidence-based research reports. It focuses on financial performance, valuation, growth, profitability, ownership trends, competitive advantages, and business risks while avoiding investment recommendations.

### Supported Modes

* Quick Take
* Deep Dive
* Compare
* Pros & Cons
* Portfolio Fit

---

## Workflow Followed

1. Opened Claude and navigated to the Skills section.
2. Created a new Custom Skill.
3. Added the skill description and detailed instructions.
4. Defined multiple analysis modes for different user requests.
5. Included mandatory rules for data sourcing, validation, and reporting.
6. Configured structured output formats.
7. Saved the skill.
8. Tested the skill using multiple stocks.
9. Generated stock analysis reports and comparison reports.
10. Verified that the skill could be reused without re-entering the prompt.

---

## Test Cases

### Test Case 1

Input:
TCS

Output:
Generated a Quick Take report including company overview, valuation metrics, profitability indicators, strengths, watch-points, and overall fundamental quality assessment.

### Test Case 2

Input:
Deep Dive on Infosys

Output:
Generated a detailed analysis covering valuation, growth, financial health, ownership trends, peer comparison, and business risks.

### Test Case 3

Input:
Compare TCS vs Infosys

Output:
Produced a side-by-side comparison of key financial and valuation metrics with a balanced summary highlighting areas where each company performs better.

---

## Key Learnings

* Custom Skills can significantly reduce repetitive prompting.
* Structured instructions improve consistency and report quality.
* Multi-mode workflows allow a single skill to handle different research tasks.
* Explicit constraints help reduce hallucinations and unsupported conclusions.
* Reusable skills can act as domain-specific assistants for recurring workflows.

---

## Challenges

* Availability of real-time financial data may vary depending on accessible sources.
* Certain advanced metrics may not always be available for every company.
* Report completeness depends on source availability and data quality.

---

## Outcome

Successfully created and tested a reusable Claude Custom Skill capable of generating structured fundamental stock research reports. The skill demonstrated consistent behavior across different analysis modes and could be reused without re-entering the original instructions.

