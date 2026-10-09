# Ata Yunus Ortak

I build football analytics tools in Python, combining match data, reproducible statistics and video tracking. My focus is turning football questions into analyses that others can run, inspect and challenge.

Currently preparing for **More Than a Hack 2027** in Barcelona.

## Featured projects

| Project | Football question | What you can inspect |
| --- | --- | --- |
| [Football Possession & xG Analysis](https://github.com/ata-yunus-ortak/football-possession-xg-analysis) | How do possession and score state relate to chance creation? | A season-snapshot case study, 1,750 score-verified matches, uncertainty intervals, explicit exclusions, and an offline synthetic demo. |
| [Football Video Analysis](https://github.com/ata-yunus-ortak/football-video-analysis) | What can tracking tell us about possession and player movement? | A tutorial-inspired prototype rebuilt around safe tracking inputs, video timing, uncertain possession, configurable calibration, and a synthetic pitch demo. |

Both projects include documented methods, runnable examples, regression tests and GitHub Actions checks. Provider data, model weights and private credentials are kept out of the repositories.

### Possession, chance volume and shot quality

[![Possession and xG case study](https://raw.githubusercontent.com/ata-yunus-ortak/football-possession-xg-analysis/main/results/overview_possession.png)](https://github.com/ata-yunus-ortak/football-possession-xg-analysis)

### Video tracking and uncertain possession

[![Synthetic football tracking demo](https://raw.githubusercontent.com/ata-yunus-ortak/football-video-analysis/main/assets/synthetic-demo.png)](https://github.com/ata-yunus-ortak/football-video-analysis)

The pitch illustration uses invented tracking data; it is a demonstration of the pipeline, not evidence of detector accuracy on match footage.

## What I am working on

- **Football statistics:** possession, chance quality, score-state analysis and data validation.
- **Computer vision:** player and ball tracking, pitch coordinates and possession estimation.
- **Reproducibility:** clear inputs, small offline demos and checks that expose data problems.

The statistical case study is descriptive; it does not establish causation. The video prototype is not a validated match-performance measurement system. Each repository explains its sources and limitations alongside its results.

## Start here

Open a project README for its visual overview, then run the synthetic example. These examples work without signing into a data provider or downloading match footage.
