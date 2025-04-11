# 2025 WNBA Draft: LA Sparks Fit Score Matrix

This project builds a team-specific draft model to evaluate 2025 WNBA prospects based on how well they fit the current Los Angeles Sparks roster. The model blends advanced stats, positional modeling, and scouting context to support smarter, role-based decision-making.

---

## What is the Fit Score Matrix?

The Fit Score Matrix ranks prospects not just by talent, but by fit — using:

- Normalized advanced stats  
- Role-based positional buckets (Guard / Wing / Big)  
- Team-specific scoring weights  
- Scouting summaries and secondary playmaking traits  

Each player receives a composite Fit Score based on how well they align with the Sparks’ roster needs, usage profiles, and defensive/spatial roles.

---

## How to Read the Matrix

Each row = 1 draft-eligible prospect  
Each column = a key role-based stat (e.g. Usage, 3PT%, DREB%, AST/TO, Help IQ)

Final Fit Score is a weighted, normalized sum of:

- Shooting (3PT%, Spacing Rating)  
- Defense (DRtg, STL%, Help IQ)  
- Versatility (AST/TO, Usage Rate)  
- Role Fit (position, creation profile)

---

## Why This Model is Sparks-Specific

Key 2025 roster moves:

- Acquired Kelsey Plum  
- Lost Nneka Ogwumike  
- Signed Mercedes Russell, re-signed Odyssey Sims

This context shifted team needs toward:

- Low-usage, high-IQ defenders  
- Frontcourt depth and rebounding  
- Wings with switchability and spacing

See [Team Context](./team_context.md) for the full breakdown.

---

## Methodology

- [Scoring Weights and Normalization](./methodology.md)  
- [Role-based Positional Tags](./scouting/)  
- [Help IQ and AST/TO scaling](./methodology.md#normalization-formula)

---

## Draft Simulations

Explore what happens if targets are off the board:

- [Pick 9: Wing vs Big dilemma](./simulations.md#pick-9-alternate-fits-if-iriafen-is-off-the-board)  
- [Pick 21: Secondary creator vs specialist](./simulations.md#second-round-pick-21-targets)  
- [Pick 28: Camp depth and spacing upside](./simulations.md#third-round-pick-28-targets)

---

## Scouting Notes

- [Top 10 Scouting Profiles](./scouting/)  
- [Extended Pool (Picks 11–30)](./scouting/extended_pool.md)

Each profile includes:
- Summary  
- Projected WNBA Role  
- Sparks Fit  
- Key Stats

---

## Visualizations

Interactive charts based on the Fit Score Matrix:

- [Top 10 Sparks Draft Fits – Tableau Bar Chart](https://public.tableau.com/views/Top10SparksDraftFits-2025/Sheet1)  
- [Spacing vs Defensive Fit – Quadrant View](https://public.tableau.com/views/SpacingvsDefensiveFit2025SparksDraftProspects/Sheet1)
- Radar: Citron vs Wing Avg – Coming Soon

---

## Data

- Raw data: [`/data/fit_score_matrix.xlsx`](./data/fit_score_matrix.xlsx)

---

## Version

v1.0 – April 2025 WNBA Draft

---

## About

Created as a capstone project for sports analytics portfolio development — with a focus on data, decision-making, and women’s basketball scouting.
