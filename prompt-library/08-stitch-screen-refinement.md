# Prompt 08: Screen Refinement for Google Stitch

**Session:** 08 — Usability Testing and Concept Testing
**Source:** Useability Testing and Concept Note.docx

## What it does

Takes rough screen descriptions and a hypothesis, and converts them into a ready-to-use prompt for Google Stitch (AI prototyping tool at stitch.withgoogle.com) to generate a working mobile app prototype.

## Required input

| Parameter | Description | Example |
|-----------|-------------|---------|
| App purpose | What the app helps users do | "Help kids learn about saving and investing" |
| Target users | Who will use it | "Kids aged 8-14" |
| Hypothesis | What users should be able to do | "Users should understand why investing beats hoarding coins" |
| Screen descriptions | 3-5 rough screen writeups | "Screen 1: what is investing?..." |

## Use cases

- Session 10 assignment: build a prototype in Stitch
- Rapid prototyping from a hypothesis
- Converting paper wireframes into a digital prototype
- Testing a concept before building in Figma

## The prompt (template)

```
I want you to refine the below screens and convert them to a ready to use prompt in Google Stitch for creating an application in mobile view to help [APP PURPOSE]. Give me a ready to use prompt with details of all the screens captured and ensure that the design, layout and the workflow is attractive for the [TARGET USERS] to use.

Here is my hypothesis-
<<[YOUR HYPOTHESIS]>>

Give my write up for the screens -
<< Screen 1: [description]
Screen 2: [description]
Screen 3: [description]
Screen 4: [description]
Screen 5: [description] >>
```

## Example (from class)

```
I want you to refine the below screens and convert them to a ready to use prompt in Google Stitch for creating an application in mobile view to help kids learn about saving, investment and basic money principles. Give me a ready to use prompt with details of all the screens captured and ensure that the design, layout and the workflow is attractive for the kids to use.

Here is my hypothesis-
<<The users should be able to understand why they should invest, rather than keeping coins in their pockets which would get expired, get wet or stolen or lose their value over time. They should understand the different money concepts.>>

Give my write up for the screens -
<< Screen 1: what is investing? user should understand what is investing and why to invest
Screen 2: then show them different options to invest like stocks(cookies, toffees) and real estate(waterpark, playground etc)
Screen 3: show the kids how the markets change like playground and water park usage would increase in summer vacation
Screen 4: show the kids disadvantage too like in winter icecream is not eaten by many So not to invest on icecream stocks
Screen 5: Track the spending and rate of increase decrease >>
```

## Workflow

1. Write your hypothesis first
2. Sketch 3-5 screens on paper
3. Describe each screen in plain language
4. Run this prompt to get a polished Stitch-ready prompt
5. Paste the output into stitch.withgoogle.com
6. Critique and re-prompt broken parts (limit ~8 edits per session)
