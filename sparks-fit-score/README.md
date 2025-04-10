# Sparks Fit Score – 2025 Draft Prospect Matching

This project evaluates 2025 NCAA WNBA Draft prospects based on their statistical and strategic fit with the **Los Angeles Sparks**. Using a weighted scoring model, roster-based trait prioritization, and contextual scouting, it builds a ranked shortlist for Picks #9, #21, and #27.

---

## Key Questions

- What traits and positions do the Sparks most need to address in the 2025 draft?
- Which NCAA prospects best align with those needs—statistically and contextually?
- Can we create a **repeatable scoring model** to assist in team-specific draft decisions?

---

## How the Fit Score Works

Each prospect is evaluated across core metrics:

- **3PT %**
- **Assist-to-Turnover Ratio**
- **Defensive Rating / DREB %**
- **Usage Rate / TS %**
- **Positional Versatility**
- **Help Defense IQ** *(qualitative)*
- **Secondary Playmaking** *(qualitative)*

Each trait is:
- **Weighted by position** (Guard, Wing, Big)
- **Normalized to a 0–100 scale**
- Aggregated into an **Overall Fit Score** and **2-Way Impact Score**

Prospects are ranked into tiers: `Top Target`, `Strong Fit`, or `Depth Option`.

[Download the Fit Score Matrix (Right Click -> Save As)](./fit_score_matrix_public.xlsx)

---

## Team Context: Los Angeles Sparks (2024)

The Sparks finished 12th in the WNBA (8–32) and ranked near the bottom in key efficiency metrics:

- Offensive Rating: **98.6** (12th)
- Assist-to-Turnover Ratio: **1.23** (11th)
- Rebounding: **32.7/game** (10th)

Key offseason moves:
- **Kelsey Plum** acquired to lead the backcourt
- **Cameron Brink** returns from injury
- **Nneka Ogwumike** departs, opening a PF void
- **Mercedes Russell** adds frontcourt depth

📄 [Full team review + draft context →](./sparks_team_review.md)

---

## Usage Guide: How to Read the Matrix

The Excel matrix includes:

- **Positionally weighted trait scores**
- **Fit Tier (Top Target, Strong Fit, etc.)**
- **Projected Pick Range**
- **2-Way Score, OTI, DTI, and Scouting Summary**
- **Draft board views** for Picks #9, #21, #27

You can also browse the full gallery of top prospects in Notion:
📎 [Sparks Draft Fit Scoreboard (Notion Gallery)](https://www.notion.so/1d19489d123c80cbb615c501fd93a9b5?pvs=21)

---

## Tools Used

- **Excel** – Scoring logic, normalization, trait weighting
- **Python** – Radar charts, trait visuals
- **Tableau** – Visual comparisons
- **Notion** – Visual player cards + trait tagging

