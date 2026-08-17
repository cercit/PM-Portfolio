# Prompt 05: User Persona Generator

**Session:** 04 — Personas, Empathy Maps and Journeys
**Source:** User Empathy Mapping, User journey and Persona.docx

## What it does

Generates a visual user persona card (1920x1080 image) with demographics, psychographics, tech proficiency, product-specific usage details, and a JSON data block. Supports primary + secondary personas.

## Required input

| Parameter | Description | Example |
|-----------|-------------|---------|
| Product name + 1-liner | What the product does | "Zepto — ultra-fast grocery delivery in Indian metros" |
| Persona count | One or two (primary + secondary) | "Two" |

## Use cases

- Session 05 assignment: build primary and secondary personas
- Quick persona generation for a PRD
- Visual deliverable for stakeholder alignment
- JSON output feeds into journey mapping or empathy mapping

## The prompt

```
You are a visual persona designer. Ask me only these two questions in one line, then proceed without further questions:
What is the product (name + 1-line what it does)?
Do you want one persona or two (primary + secondary)?

After my reply, generate an image (1920x1080 PNG) with a clean poster layout: title "CASE STUDY — USER PERSONA", subtle paper texture background, two rounded persona cards (left = Primary, right = Secondary; if I choose "one", center a single large card). Include a small product logo placeholder top-right. Use modern typography, clear section headers, bullet points, and high contrast. Add friendly, diverse face placeholders (no real people). Keep language respectful and stereotype-free.

For each persona card, fill these sections with crisp, specific bullets tailored to the product's market (invent realistic details when missing):
- Name (label: "User") + short 1-line life with the product ("A day in one sentence").
- Demographics: Age range, Location (city/region), Occupation, Income band, Relationship/Household if relevant, Digital literacy.
- Psychographic: Pains (top 3), Gains (top 3), Motivations, Values, Fears.
- Tech Proficiency: Devices, OS, App habits, Social media usage, Internet constraints (data caps/latency), Accessibility needs if any.
- Product-Specific: Current solutions/alternatives, Usage scenarios & frequency, Purchase drivers, Satisfaction level, Switching barriers, Success metric they care about.
- What they want: 3-5 crisp outcome-oriented statements (e.g., "set-and-forget automation," "transparent pricing").

Visual formatting rules:
Use the section labels exactly: Demographics, Psychographic, Tech Proficiency, Product-Specific, What they want.
Keep each bullet <=12 words; 4-6 bullets per section.
Highlight Pains and Gains with small icons or bold labels.
If two personas, make the Secondary clearly distinct (different goals, context, constraints).

Output:
Primary deliverable: a single image (1920x1080 PNG) containing the formatted persona card(s).
Also include a compact, copyable JSON block below the image mirroring all fields for each persona (keys: name, life_with_product, demographics, psychographic {pains, gains, motivations, values, fears}, tech_proficiency, product_specific, wants).
Do not ask more questions. If any info is unknown, infer plausibly from the product description and state assumptions subtly in the JSON under assumptions.

Accessibility & ethics:
Avoid stereotypes; ensure inclusive language; no sensitive attributes unless essential and respectful.
Use generic/AI headshots, not identifiable people.

Begin now by asking only: "Product (name + 1-liner)? One persona or two (primary + secondary)?"
```
