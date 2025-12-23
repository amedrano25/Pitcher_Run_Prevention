# Pitcher Run Prevention: Arsenal Evaluation and Matchup-Based Game Planning

## Overview
This project evaluates a pitcher’s run prevention profile through pitch-level arsenal analysis, command assessment, and hitter-specific game planning. Using tracking data, the analysis focuses on identifying which pitch characteristics, usage patterns, and location tendencies most effectively suppress damage and miss bats, and how those insights translate into actionable matchup strategies against a specific hitter.

The project mirrors a front-office style workflow, emphasizing decision-making, justification, and practical application rather than purely descriptive metrics.

---

## Objectives
- Evaluate Pitcher B’s pitch arsenal in terms of shape, usage, stuff, and command
- Identify strengths, weaknesses, and potential inefficiencies in Pitcher B’s repertoire
- Analyze year-over-year or contextual changes that impact run prevention
- Propose data-backed adjustments to pitch usage and sequencing
- Construct a hitter-specific game plan against Position Player A based on matchup advantages

---

## Data
The analysis uses pitch-level and batted-ball data provided as part of an analyst evaluation exercise.

**Primary datasets:**
- Pitcher B pitch-level tracking data
- Position Player A pitch-by-pitch hitting data

Key fields include (where available):
- Pitch type
- Velocity and movement metrics
- Plate location (`plate_x`, `plate_z`)
- Swing, whiff, and contact outcomes
- Count and situational context

---

## Methodology

### Pitcher Arsenal Evaluation
Pitcher B’s arsenal is assessed using:
- Pitch usage and strike percentage
- Movement profiles (horizontal vs induced vertical break)
- Whiff rates and contact quality by pitch type
- Location heatmaps to evaluate command and miss tendencies
- Count-based pitch usage to assess trust and sequencing

These components are used to distinguish between “strike-throwing” pitches and true run-prevention tools.

---

### Run Prevention Analysis
Run prevention is evaluated through:
- Swing-and-miss ability (whiff and CSW rates)
- Contact quality suppression (xwOBA, exit velocity, slugging where available)
- Location consistency and avoidance of damage-prone zones
- Alignment between pitch effectiveness and usage patterns

---

### Matchup-Based Game Planning
A hitter-specific game plan is developed by:
- Identifying Position Player A’s pitch-type strengths and weaknesses
- Analyzing hot and cold zones by contact quality
- Evaluating chase and whiff tendencies by count
- Aligning Pitcher B’s strongest pitches and locations with Player A’s vulnerabilities

The resulting plan outlines early-count, neutral-count, and two-strike strategies designed to minimize run expectancy per plate appearance.

---

## Visualizations
Key visualizations used throughout the analysis include:
- Pitch movement plots (HB vs IVB)
- Pitch usage and strike percentage bar charts
- Whiff rate and damage allowed by pitch type
- Pitch location heatmaps by pitch type
- Count-based pitch usage breakdowns

Each visualization is designed to answer a specific baseball question and directly support analytical conclusions.

---

## Tools & Technologies
- Python
  - pandas
  - matplotlib
  - seaborn
- Jupyter Notebooks

All analysis is fully reproducible and structured to support clear communication of findings.

---

## Key Takeaways
- Identifies which pitches most effectively contribute to run prevention
- Highlights potential inefficiencies in pitch usage and sequencing
- Demonstrates how pitcher traits can be leveraged in hitter-specific game planning
- Emphasizes actionable insights over purely descriptive statistics

---

## Project Structure
Pitcher_Run_Prevention/
│
├── data/ # Raw and processed datasets
├── notebooks/ # Analysis notebooks
├── visuals/ # Exported plots and figures
├── README.md


---

## Notes
This project is intended to demonstrate analytical approach, reasoning, and communication style consistent with professional baseball analytics roles. All conclusions are based solely on the provided datasets and do not represent real-world player evaluations.
