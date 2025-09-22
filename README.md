# choose-the-right-chart-LP(learning project)
An interactive Tableau workbook and reference guide that helps data practitioners choose the most effective chart for a given question and dataset. 
The project is designed as an educational tool for analysts, engineers, product managers, data scientists, and anyone who turns data into decisions.

## Overview
This repository contains a Tableau workbook, and screenshots to help you learn when and why to use common chart types. 
The dashboard guides you through a decision flow: from business question → data shape → recommended chart(s), with side-by-side examples and practical configuration tips.

The goal is to make chart selection deliberate, reproducible, and audience-aware — not just aesthetic.

## Key Features
- **Interactive Chart Selector:** Pick your objective (change over time, magnitude, correlation, distrubution etc...) and the data characteristics (categorical vs numeric, time series, number of categories) to get chart recommendations and examples.  
- **Paired Examples & Alternatives:** Side-by-side visualizations showing the same data rendered with different charts, plus pros/cons for each option.  
- **Try-It Sandbox:** Small sample datasets and adjustable parameters so you can test chart choices in real time and see the impact of sorting, aggregation, and filters.  

## Files in this repository
- `README.md` — this file  
- `screenshots/` — images of the dashboard for quick preview, additional guides from Andrew Abela's Chart chooser

## How to open / use
1. click tableau publick link
   link: tableau public (https://public.tableau.com/app/profile/rowel.andrew.legaspi/viz/ChoosetheRightChart/Story1)

## Design & UX notes
- **Decision-first approach** Start with the question you need to answer (e.g., "Which product subcategory grew fastest?") before choosing visualization types.
- **Highlight extremes and averages** Mark highest/lowest points and show average lines for quick benchmarking.
- **Small multiples** Use small multiples (trellis) to show consistent comparisons across many categories without relying on color alone.
- **Avoid over-aggregation** Preserve the right level of detail for the question; aggregated views are useful for summaries but can hide important patterns. 
- **Accessibility** Prefer color palettes with good contrast, include direct value labels when appropriate, and avoid color-only encodings.

## Credits
Special thanks to **Baraa Khatib Salkini** for the guidance that inspired the structure and teaching approach used in this workbook.
**Project:** Interactive Tableau dashboard for Sales & Customer analytics

## Contact
Rowel Andrew Legaspi (Drew)  
- LinkedIn: https://www.linkedin.com/in/rowel-andrew-legaspi-289936241/
- Tableau Profile: https://public.tableau.com/app/profile/rowel.andrew.legaspi
