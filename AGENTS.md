# AGENTS.md -- BDC Satria Data 2026

You are an **expert machine learning engineer** specializing in computer vision. Your goal is **maximum Macro F1-Score** on 3-class classification (Recyclable, Electronic, Organic). Read `docs/` before working to understand the full context.

## Competition essentials

- **Task**: Classify waste images into 3 classes (0=Recyclable, 1=Electronic, 2=Organic)
- **Metric**: Macro-averaged F1-Score (not accuracy)
- **Data**: ~26,527 labeled train images (in class subfolders), 1,458 unlabeled test images
- **Download**: `https://bit.ly/datasetbdc2026`
- **Template**: `https://bit.ly/submissionbdc2026`
- **Constraints**: Visual features only, no external/labeled data allowed, pre-trained models OK

## Project structure

```
data/raw/          # original dataset (gitignored)
data/processed/    # cleaned dataset (gitignored)
notebooks/         # EDA, experiments, final pipeline
src/utils.py       # helper functions (stub)
outputs/figures/   # plots (gitignored)
outputs/models/    # saved weights (gitignored)
outputs/submissions/ # CSV submissions (gitignored)
docs/              # full competition context (4 files)
```

## Key gotchas

- **No test/lint/typecheck** framework configured
- **Submissions**: max 3 per team, CSV named `submission_NamaTim.csv`, columns `id,predicted`
- **Deadline**: 30 July 2026, 16:00 WIB (UTC+7)
- **Top 22 teams** advance to semifinal; proof video required
- **Data is gitignored** -- download dataset first before running any notebook
- **Google Drive data links** (used by notebook setup cells):
  - Train: `https://drive.google.com/drive/folders/1mVsWMnr2nmRotVjndbej9ONQmM6y5-q9`
  - Test: `https://drive.google.com/drive/folders/1s9X4xtl5XeR9Fpmtw7WVTHfKozkUylM4`
  - Submission template: `https://drive.google.com/file/d/1GiRvwB13vCmHXcPmkr9EoTBaDS9RjXQ7`
- **docs/ files are in Indonesian** -- refer to them for competition rules, constraints, and disqualification conditions

## Notebook conventions

- **1 cell = 1 logical unit** (1 output or none). Never merge multiple independent outputs into one cell.
- **Python 3.12** (system installed, no virtual env).
- **Markdown style**:
  - Centered title with `<div align="center">` for the project/notebook title.
  - Main sections: `## ***Section Name***` followed by `---`.
  - Subsections: `### ***Subsection Name***` (no horizontal rule).
  - No emoji, no decorative filler.
  - Short explanations scoped to the current group.
  - Write conclusions after running and inspecting the output, not before.
