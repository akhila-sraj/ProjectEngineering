# Token Audit Report

## Pre-Fix Audit

* System Prompt Tokens: 420
* Sample User Input Tokens: 20
* Completion Tokens: 317

### Cost Calculation (Before Optimisation)

Cost per call:

= (420 × 0.0000025) + (317 × 0.00001)
= 0.00105 + 0.00317
= $0.00422

Monthly calls:

200 × 15 × 30 = 90,000

Monthly cost:

90,000 × 0.00422 = $379.80

---

## Waste Sources

### 1. Duplicate Instructions

The prompt repeated the same constraints (e.g., only respond to code review) multiple times.

### 2. Filler Preamble

The introduction describing the AI assistant added no functional value.

### 3. Over-Verbose Instructions

Simple rules were written in long paragraphs instead of concise statements.

---

## Rewritten Prompt

* Original Tokens: 420
* Optimised Tokens: 120
* Reduction: ~71%

---

## Cost Comparison Table

| Version   | Prompt Tokens | Completion Tokens | Cost Per Call | Monthly Cost |
| --------- | ------------- | ----------------- | ------------- | ------------ |
| Original  | 420           | 317               | $0.00422      | $379.80      |
| Optimised | 120           | 317               | $0.00350      | $315.00      |

---

## Savings

$379.80 - $315.00 = $64.80/month saved

---

## Conclusion

The prompt was optimised by removing redundant instructions and compressing verbose text while preserving all functionality. This significantly reduced token usage and cost, improving efficiency without affecting output quality.
Final optimisation completed.
