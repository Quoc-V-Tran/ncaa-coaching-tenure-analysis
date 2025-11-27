# NCAA Head Coach Tenure and Performance (Work in Progress)

This project explores how **NCAA football head coach tenure** and **team performance** (win percentage) have evolved over time, and how tenure relates to factors like:

- Coach experience
- Power 5 vs non–Power 5 conference
- Era of college football (e.g., pre–playoff vs playoff era)

The goal is to build a panel-style dataset of school–year–coach combinations and model:

- Win percentage as a function of coach, school, and era
- How **average head-coaching tenure has changed over time**
- What this implies for **contract design** and performance expectations.

> Note: This repo is currently a **work in progress**. The notebook focuses on data assembly and early exploratory analysis; modeling and write-up are still being refined.

---

## Current Status

So far, the notebook covers:

- Scraping and/or loading coach records from NCAA/school sources
- Cleaning head coach tenure by school and season
- Basic summaries of:
  - Average tenure length over time
  - Differences between Power 5 and non–Power 5 programs

Preliminary takeaway (subject to refinement):

- Average head-coaching tenure appears to have **shortened by roughly half** compared with earlier eras, especially in Power 5 conferences.
- This supports the idea that schools and coaches should **price shorter cycles and performance-based triggers into contracts**, rather than assuming long stable tenures.

---

## Next Steps

Planned work:

- Build a panel dataset at the (school, season, coach) level
- Add win percentage and strength-of-schedule measures
- Fit fixed-effects / random-effects models for win percentage vs:
  - Coach experience
  - School/program effects
  - Era and conference
- Refine tenure change estimates and visualizations

---

## Repository Structure

Planned structure:

- `data/` – cleaned coach records and any derived panel data (to be added)
- `R/` – current exploratory notebook
- `README.md` – this file

---

## How to Use

Right now, this repo is mainly for **showing work in progress**:

1. Clone the repo.
2. Open `notebooks/ncaa_coach_tenure_exploration` in Jupyter or RStudio (depending on format).
3. Run cells to follow the data cleaning and initial analysis.

As the project matures, this README will be updated with full model details and finalized conclusions.
