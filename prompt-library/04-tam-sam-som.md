# Prompt 04: TAM SAM SOM Market Sizing

**Session:** 05 — Competitor Research and Analysis
**Source:** Class 5 - Competitor Research and Feature Analysis_.docx

## What it does

Interactive step-by-step market sizing. The AI walks you through clarifying questions about product, geography, target segment, and output format, then generates TAM/SAM/SOM numbers with source citations and an executive summary.

## Required input

| Parameter | Description | Example |
|-----------|-------------|---------|
| Product/solution | What you're sizing the market for | "10-minute grocery delivery" |
| Industry | Which sector | "Quick commerce" |
| Geography | Region to focus on | "India, tier-1 and tier-2 cities" |
| Target segment | B2B/B2C, demographics | "B2C, urban 18-45, smartphone users" |
| Sizing format | Revenue, customers, or both | "Both" |
| Audience | Who will read this | "Product team" |

## Use cases

- Session 06 assignment: TAM, SAM and SOM sizing
- Business case for a new feature or product
- Investor pitch preparation
- Chains from Prompts 02 and 03 to complete the three-step analysis chain

## The prompt

```
You are my interactive strategy analyst. Guide me step by step to size the market opportunity for a new product.

Start by asking me: "What is the product/solution and which industry are you targeting?"
Next ask: "Which geography/region(s) should we focus on first?"
Then ask: "Who is the target customer segment, and what are their key characteristics (B2B/B2C, income, company size, demographics)?"
Ask: "Do you want the sizing in revenue, customer numbers, or both?"
Clarify: "What sources or assumptions (reports, CAGR, benchmarks) should we rely on, or should I suggest defaults?"
At each step, confirm inputs before proceeding.
Generate TAM, SAM, and SOM sizing in a concise format (<=200 words, OR a clean table, OR a simple image).
Ask me: "Which output format do you prefer — text summary, table, or image?"
Provide a final executive summary with 3-4 key insights highlighting growth opportunity, risks, and addressable market.
Before finalising, ask: "Who is the target audience for this analysis (executives, investors, product team, or cross-functional stakeholders)?" so the tone can be tailored.
```
