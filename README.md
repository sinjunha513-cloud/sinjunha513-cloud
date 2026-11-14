# Junha Shin

**Undergraduate at Kookmin University | Sports analytics and movement understanding**

I study Sports Health and Rehabilitation and use sports projects to explore data analysis and application development. My long-term interest is understanding player movement from football video and learning how game situations evolve.

## Research interests

Access to tracking data for the leagues and matches I want to study has been a practical constraint. I would like to learn how to estimate player positions and movement from video, account for occlusion and camera motion, and study interactions and future motion.

I am particularly interested in the connection between visual representations, learned dynamics, and action-conditioned prediction. These are proposed research directions; I have not yet trained a player-tracking or world model.

## Project experience and use of GPT

The projects below were developed with substantial GPT assistance for code generation, revision, and debugging. I am still developing the ability to read, modify, and debug Python independently. The repositories show the scope and outputs of my project work, with limitations and evaluation status stated explicitly.

## Selected projects

### [K League 1 High Turnover and Attacking Transition Analysis](https://github.com/sinjunha513-cloud/K-league_high_turnover_analysis)

**Individual project · 2 months · GPT-assisted analysis**

- An event-based study of attacking transitions using 2024 K League 1 data from **198 matches and 12 teams (rounds 1–33)**.
- The analysis distinguishes changes in the event-performing team from inferred changes in possession and tracks attacks for up to **15 seconds**.
- The revalidated analysis identifies **5,290 high-turnover sequences**, with **1,211 (22.9%)** linked to a first shot within 15 seconds.
- Revalidation includes duplicate checks, final-score reconciliation for all 198 matches, sensitivity analyses, and match-clustered association estimates. The report explains remaining limits of event-derived possession and timestamp ambiguity; these results do not establish causal effects.

This project provides the motivation for my interest in the movement and interactions that event records do not continuously capture.

[Code and methods](https://github.com/sinjunha513-cloud/K-league_high_turnover_analysis) · [Illustrated PDF report](https://github.com/sinjunha513-cloud/K-league_high_turnover_analysis/blob/main/reports/K_League_High_Turnover_Report.pdf)

### [AI Scouting Platform](https://github.com/sinjunha513-cloud/AI-Scouting-Platform)

**Three-person team · 3 months · Platform and ML logic with GPT assistance**

My role covered platform development and scoring, clustering, and recommendation logic with GPT assistance.

- Streamlit interface for player comparison and statistical exploration.
- Season- and position-specific standardization, configurable scoring, per-90 count handling, and missing-data coverage indicators.
- K-Means grouping and cosine-similarity-based recommendations.
- Fictional sample data for exploring the app; real-world scouting accuracy has not been evaluated.

[Code and methodology](https://github.com/sinjunha513-cloud/AI-Scouting-Platform) · [Live demo](https://junha-ai-scouting.streamlit.app/)

### [ONEPOINT Sports Coaching Platform](https://github.com/sinjunha513-cloud/ONEPOINT)

**Individual project · 6 months · GPT-assisted application development**

A Flutter and Firebase application under development, with workflows for coach discovery, lesson availability and applications, role-based access, and messaging.

This project gave me practical exposure to application development and client–backend integration using AI coding assistance. A web demo and walkthrough show the current interface; production readiness has not been established.

[Code and project scope](https://github.com/sinjunha513-cloud/ONEPOINT) · [Web demo](https://onlyonepoint-lesson.web.app) · [Walkthrough video](https://github.com/sinjunha513-cloud/ONEPOINT/blob/main/demo/onepoint-demo.mp4)

## Background

- Sports Health and Rehabilitation, Kookmin University — transfer admission in March 2025; expected graduation in February 2027.
- One year of sports analytics research activities in **KODE**, Kookmin University's sports analytics club.
- Coursework includes biomechanics, sports statistics, AI sports programming, sports data analysis and applications, and measurement and evaluation.

## Tools encountered through project work

Python, Pandas, NumPy, scikit-learn, Matplotlib, Plotly, Streamlit, Jupyter Notebook, Flutter/Dart, Firebase, and GitHub. This list describes project exposure, not equal proficiency in every tool.

My next learning priorities are independent Python programming, code and result validation, and the foundations needed for PyTorch-based training and evaluation.
