# Investment — Final Exam Study Guide

A self-contained, beginner-friendly HTML study guide covering four chapters of an EMBA Investment course:

1. **Bonds & Their Valuation**
2. **Stocks & Their Valuation**
3. **Options Contracts**
4. **Risk & Return** (with statistics primer)

Plus a **Practice Exam** section.

## Live page

Open the deployed page here: **https://amsamms.github.io/investment-final-study/**

## What's inside each chapter

- Plain-English vocabulary (every term defined the first time it's used — zero-knowledge reader)
- Every formula derived with multiple worked numerical examples
- Interactive widgets (bond pricer, stock pricer, option payoff explorer, risk calculator)
- Chart.js diagrams (pull-to-par, price–yield sensitivity, terminal-value dominance, payoff curves)
- "Exam traps" section with the question patterns that show up on past finals
- Collapsible flashcards
- Recap card at the end

## Tech stack

- Single self-contained HTML file (`index.html`) — no build step, no server, opens in any modern browser.
- KaTeX (CDN) for math rendering.
- Chart.js (CDN) for plots.
- Google Fonts (Inter, Lora, JetBrains Mono).
- Vanilla JavaScript for tab switching and interactive widgets.

## How to use locally

```bash
git clone https://github.com/amsamms/investment-final-study.git
cd investment-final-study
# Open index.html in any browser, or:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Made by

Ahmed Sabri
