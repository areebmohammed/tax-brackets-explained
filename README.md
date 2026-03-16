# Tax Brackets Explained

An interactive data visualization that demystifies the U.S. federal income tax bracket system. Built to debunk the common myth that crossing into a higher bracket taxes all of your income at the new rate.

## Live Demo

[areebmohammed.github.io/tax-brackets-explained](https://areebmohammed.github.io/tax-brackets-explained)

## Features

- **Standard Deduction Visualizer** — shows how your gross income splits across the sheltered deduction, federal tax owed, and take-home pay across all three filing statuses
- **Bracket Visualizer** — drag any income level to see a real-time breakdown of tax owed per bracket, marginal rate vs. effective rate, and a bracket-by-bracket contribution chart
- **Myth vs. Reality Chart** — plots the "all income taxed at top rate" myth against actual progressive tax across the full income range
- **Filing Status Comparison** — side-by-side bracket width chart for Single, Married Filing Jointly, and Head of Household filers
- **Marriage Bonus/Penalty Calculator** — heatmap showing where filing jointly saves money vs. costs more for any combination of two incomes
- **Historical Top Rate Chart** — traces the top marginal rate from 1913 to 2024 with annotated historical context for major policy shifts

## Tech Stack

- Single-file HTML/CSS/JavaScript — no frameworks, no dependencies
- Canvas API for all custom chart rendering
- Hosted on GitHub Pages

## Project Structure

```
index.html    # entire app — markup, styles, and chart logic in one file
```

## Running Locally

No build step needed. Just open the file:

```bash
open index.html
```

Or serve it locally to avoid any browser file-access restrictions:

```bash
npx serve .
```

## Data Sources

- IRS Rev. Proc. 2023-34 (2024 tax year brackets and standard deductions)
- Tax Foundation historical top marginal rate data

---

Built for CSE 442 Data Visualization — University of Washington, 2024
