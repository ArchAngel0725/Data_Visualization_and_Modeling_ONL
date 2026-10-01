# Course Notes

A running log of decisions and things worth remembering while working through the labs.

## Setup
- Run notebooks in **JupyterLab** (Anaconda Navigator). Use **VS Code** only for git (Source Control, `Ctrl+Shift+G`: commit, then Sync Changes).
- Fork: `ArchAngel0725/Data_Visualization_and_Modeling_ONL`. The repo was re-cloned fresh on 2026-09-28, so work restarts at Week 1.
- If a variable or column "doesn't exist," check that the earlier cells were actually run. Kernel state depends on run order, not page order. **Restart & Run All** before submitting.

## Week 1

**Lab – Data Visualization and Visual Thinking** (do first; Reproducible Workflow lab second)
- Done: load/inspect, feature table, destination bar chart, delay histograms (default/5/25 bins), `.describe()`/`.mode()`, truncated-axis demo, representativeness Q1–4.
- Key numbers: 5,000 flights; delay min -55, max 953, mean 6.1, median -6, mode -8 → right-skewed. Top destination: Chicago, IL (~297).
- Lesson learned: a histogram takes the raw column, not `.value_counts()`; histograms do their own counting.
- Also done: representativeness Q5, Choosing a chart (airline = bar, 13 airlines; early/on-time/late = pie, 3 parts of a whole; distance = histogram).
- Next: Explore a dataset of your own (find CSV + data dictionary, save in `week01/lab/data/`) → AI reflection → Restart & Run All → commit/push.
- Own-dataset idea: county wages vs. living cost (BLS county wages + MIT Living Wage Calculator) for rural western NC.

## To learn later
- How sea surface temperature drives hurricane **rapid intensification**, and why it's becoming more frequent. Check NOAA/NHC sources. (From the week 3 hurricane lab discussion.)
