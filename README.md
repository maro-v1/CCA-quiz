# CCA Foundations Practice Quiz

An unofficial practice quiz for the Claude Certified Architect (CCA) Foundations exam. Runs entirely in the browser — no install, no server.

**Live:** https://maro-v1.github.io/CCA-quiz/

## How to run

Visit the live app at https://maro-v1.github.io/CCA-quiz/, or clone the repo and open `index.html` locally for offline use.

## Features

- 60 randomly selected questions from a bank of 500+
- **Immediate Feedback** mode — see the correct answer and explanation after each question
- **Review at End** mode — answer all questions, then submit for a full results breakdown
- Progress is saved to `localStorage` and survives page refresh
- Load additional questions beyond the initial 60 without repeats

## Project structure

| File | Purpose |
|------|---------|
| `index.html` | App UI, styles, and all application logic |
| `questions.js` | Global `QUESTIONS` array loaded by `index.html` |
| `ccaf_questions_consolidated.json` | Source question data (id, question, options, correctAnswer, explanation) |

## Disclaimer

This is an unofficial study tool. Questions may not reflect the actual CCA Foundations exam. Use for study purposes only.
