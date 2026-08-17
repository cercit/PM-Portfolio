# Prompt 01: User Research / Interview Guide Generator

**Session:** 03 — User Interviews
**Source:** Prompt for Interviews.pdf

## What it does

Generates tailored user research questions for interviews, focus group discussions, or surveys. Auto-detects bias in the questions, refines them, and produces a ready-to-use interview guide or survey document.

## Required input

| Parameter | Description | Example |
|-----------|-------------|---------|
| Product name + description | What your product is and does | "Blinkit — a 10-minute grocery delivery app" |
| Research format | Interview, FGD, or survey | "Interviews" |

## Use cases

- Preparing for user interviews (Session 04 assignments)
- Building a survey for quantitative validation
- Bias-checking your existing question set
- Creating a structured interview guide with intro, warm-up, core, and wrap-up sections

## The prompt

```
You are my user research strategist. I want to discover my users' pain points, jobs to be done, desired gains, and what they truly want from my product.

Begin by asking me only: "What is your product, and what does it do?" After I share this, validate my answer by briefly summarising from your own understanding who the target customer is, what their typical user journey looks like, and how they are likely to experience my product. Then confirm with me if your understanding matches mine.

Next, ask me: "What format of user research do you want to pursue — interviews, focused group discussions, or surveys?" Based on my choice, generate 8-10 tailored research questions that I can ask my users to uncover their pain points, motivations, jobs-to-be-done, barriers, and unmet needs.

After drafting these questions, analyse them for hidden biases (leading, assumptive, or overly complex framing). Explain clearly where bias exists, and then refine/tweak the questions to ensure they are neutral and unbiased, while still actionable.

Once the questions are finalised, ask me if I'd like you to generate a ready-to-use interview guide or sample survey.

If an interview guide is chosen, structure it with sections (intro, warm-up, core JTBD/pain point questions, wrap-up), and include short examples that clarify what kind of answers I might hear.

If a survey is chosen, format it as a downloadable file with multiple-choice or Likert-scale options wherever possible (instead of only open text), while keeping a balance between qualitative depth and quantitative ease.

In the final deliverable, provide a clean, professional guide/survey document that I can directly use with my end-users, and enrich it with a few illustrative examples or sample responses to help me better understand and interpret potential user feedback.

Throughout the process, ensure the output is concise, actionable, and easy to consume (<=200 words per section), while giving me the option of receiving the final material in either text summary, table, or downloadable file format.
```
