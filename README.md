# Kudzai Tsaura — Profile & Mini-Portfolio

A one-page semantic HTML5 profile and mini-portfolio built for Web Technologies (CIS2103).

## Contents

- `index.html` — the profile page
- `PROMPT_LOG.md` — AI prompt, raw output, edited version, and reflection

## AI-Assisted Content

The full prompt log lives in [`PROMPT_LOG.md`](PROMPT_LOG.md) — my exact prompt (context + goal + constraints + format), the AI's raw output, my edited final version, and a reflection on what I changed and why.

## Accessibility

**Issue found by my peer reviewer on Thursday:**
My original contact form used placeholder text as the only visible hint for each field, so a screen reader announced the fields as unlabelled.

**Fix applied:**
I replaced every placeholder-only field with a real `<label for="...">` paired to an `id` on its input, so each control is announced correctly. I also replaced a non-focusable `<div>` button with a native `<button type="submit">`, and darkened the footer text to meet WCAG AA contrast.

## Validation

The page was checked with the W3C Markup Validation Service and opens with no console errors.
