# Selected project portfolio

Junha Shin · Kookmin University · Research internship portfolio  
Submission snapshot reviewed on 14 November 2026.

These projects were developed with substantial GPT assistance. Independent Python implementation and debugging skills are still developing. “Submission snapshot” identifies the reviewed portfolio version; it does not mean a production release or a completed research publication.

## Suggested reading order

| Project | Start here | Scope and evaluation |
| --- | --- | --- |
| K League high turnovers | [Illustrated report](https://github.com/sinjunha513-cloud/K-league_high_turnover_analysis/blob/dafdba31b7a0ae9d1338ccdd4dc8094874509fd2/reports/K_League_High_Turnover_Report.pdf) · [Notebook](https://github.com/sinjunha513-cloud/K-league_high_turnover_analysis/blob/dafdba31b7a0ae9d1338ccdd4dc8094874509fd2/전방탈취_최종본.ipynb) | Individual, 2 months. 198 matches, rounds 1–33; 5,290 turnovers and 1,211 first-shot links. Revalidation, sensitivity checks and match-clustered inference. Event-derived possession; no video ground truth or causal claim. |
| AI Scouting Platform | [Methods and source](https://github.com/sinjunha513-cloud/AI-Scouting-Platform/tree/7fd39731b62721c777f746de925f38dfc0c25903) · [Demo](https://junha-ai-scouting.streamlit.app/) | Three-person team, 3 months. My role: platform development and ML logic. Standardization, per-90 counts, missing-data coverage, K-Means and cosine similarity. Fictional demonstration data; real-world scouting accuracy untested. |
| ONEPOINT | [Source and screenshots](https://github.com/sinjunha513-cloud/ONEPOINT/tree/7d6c0dec8be5dcddfd0b873773b425293fc6a813) · [Walkthrough](https://github.com/sinjunha513-cloud/ONEPOINT/blob/7d6c0dec8be5dcddfd0b873773b425293fc6a813/demo/onepoint-demo.mp4) | Individual, 6 months. Flutter/Firebase coaching app in development. Demonstrates application workflows; live payment and production readiness are not established. |

## Verification status

- K League: raw-data rerun reproduced the earlier baseline; revised script and executed notebook agree. Final scores reconcile for 198/198 matches. Ten boundary-case tests pass. The report explains simultaneous timestamps and remaining uncertainty.
- Scouting: the current repository's suite ran 12 tests: 11 passed and one local-workbook test was skipped because no workbook was supplied. These checks validate implementation behavior, not recruitment success.
- ONEPOINT: source, README, walkthrough and screenshot paths were inspected. Flutter execution and end-to-end production validation were not performed in this final review.

## Research motivation

Event records do not continuously capture player positions and interactions. My proposed next step is learning to evaluate video-based tracking, quantify tracking uncertainty, and study short-horizon motion prediction. Visual world models and action-conditioned simulation are longer-term interests, not completed work.

Raw match data and academic transcripts are not published here. The CV and research statement are provided directly with the application email.
