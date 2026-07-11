# AI Prompts — Placeholder Section (FAQ)

## Section chosen
**Frequently Asked Questions (FAQ)** — placed after the "Secure Your Spot" pricing section.

## Tool used
Google Gemini

## Prompt used
A full screenshot of the DevConf 2026 page (with the "Something Missing? Generate a relevant section with AI" placeholder) was shared with Gemini, along with the following prompt:

> "Eibar bolo, pura website er picture dici. Something Missing? section a ki deya jai?"
> (Now tell me — I've given the full picture of the website. What can be put in the "Something Missing?" section?)

Gemini suggested a few options; the reply given was:

> "Ami FAQ section dite cacci"
> (I want to add an FAQ section.)

Gemini then generated FAQ content and structure ideas for the section, which were adapted into the final HTML/CSS implementation on the page.

## What was manually adjusted after AI output
- Rewrote/edited FAQ content to match the site's tone and avoid duplication
- Implemented the section using native `<details>`/`<summary>` (no JavaScript)
- Styled it manually to match the existing design system (colors: #0D1B2A navy, #1D4ED8 blue accent, #575757 gray text) with a custom +/− indicator