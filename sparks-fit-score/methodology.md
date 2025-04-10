# Methodology

## Overview

The **Fit Score Matrix** was created to evaluate 2025 WNBA Draft prospects through the lens of *team-specific fit* for the Los Angeles Sparks. Rather than focusing solely on traditional draft rankings or raw potential, this model prioritizes how well a player’s statistical and stylistic profile aligns with the Sparks' current roster construction, strategic needs, and on-court philosophy.

This methodology blends **advanced statistics**, **scouting context**, and **positional modeling** to offer a data-informed draft tool tailored for decision-making.

---

## Stat Selection & WNBA Translation

Each statistical category was chosen for its relevance to *WNBA-level translation* and its ability to reflect a prospect’s likely role impact. Stats were grouped into thematic buckets:

- **Defensive Impact**  
  Defensive Rating, Block Rate, Steal Rate, Synergy defensive grades

- **Shooting Efficiency**  
  3P%, True Shooting %, Catch-and-Shoot scoring metrics

- **Versatility**  
  Assist Rate, Usage %, Transition/Cutting metrics

- **Rebounding & Size Indicators**  
  Rebound Rate, Height/Wingspan (where available)

- **Secondary Creation**  
  Pick-and-roll possessions, Isolation usage, Assist/Turnover ratio

These metrics were selected not only for reliability but also for how well they reflect success in **role-specific contexts**, particularly for rookies entering the WNBA in limited minutes or complementary positions.

---

## Positional Fit Framework

Instead of rigid positional labels (PG, SG, SF, PF, C), this model uses a flexible, role-based grouping:

- **Guards** – Primary or secondary ball-handlers, on-ball creators, defensive pressure guards  
- **Wings** – Perimeter defenders, spot-up shooters, cutters, switchable on D  
- **Bigs** – Interior finishers, rebounders, shot blockers, post defenders

This system better reflects modern WNBA usage, where **positional overlap and lineup fluidity** are common. Each player was tagged according to functional role, not traditional height-based designations.

> **Example**: Jacy Sheldon’s fit as a low-usage off-ball guard was weighted more positively than a high-usage primary guard like Charisma Osborne, due to the Sparks’ existing ball-handlers and emphasis on spacing and defense.

---

## Scoring Weights

Each statistical trait was **normalized** and then **weighted** based on its relevance to the Sparks' 2025 needs. Weightings were established through a blend of:

- Team-specific gaps (roster audit)  
- Projected role usage  
- Positional depth in this draft class

### Normalization Formula

Most statistics were normalized using z-scores:

Z = (X - μ) / σ

Where:  
- *X* = player's stat  
- *μ* = positional average  
- *σ* = positional standard deviation

In some cases, **percentile rankings** were used for traits with skewed distributions or to allow easier comparison across positions.

---

### Weighting Table

| Category              | Weighting Priority | Rationale |
|----------------------|--------------------|-----------|
| Defense              | High               | Sparks lacked consistent wing and point-of-attack defense |
| Shooting Efficiency  | High               | Spacing needed to complement Plum and Hamby |
| Versatility          | Medium             | Two-way, switchable players valuable across positions |
| Secondary Creation   | Low–Medium         | Can’t be a non-creator, but creation isn’t top priority |
| Usage / Role Fit     | High               | Low-usage, high-impact players preferred |

Each prospect’s final **Fit Score** reflects a weighted composite of their positional fit, statistical impact, and functional relevance to the Sparks' system.

---

## Data Sources & Tools

All statistical data was sourced from **Her Hoop Stats** (2024–25 NCAA season). Players with limited sample sizes or insufficient minutes were filtered out during preprocessing.

This model was built and refined using:

- Google Sheets (Fit Score Matrix)  
- Python (for stat normalization
