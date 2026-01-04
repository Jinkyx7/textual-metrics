# Textual Metrics

Notebook-driven metrics for annual report text. The main workflow lives in
`textual_metrics.ipynb` and reads CSV inputs from `reports/` to compute and
summarize metrics (length, boilerplate, fog, and related measures).

## Quick Start
1. Install Python 3 and Jupyter.
2. Launch the notebook:
   ```bash
   jupyter lab
   ```
3. Open `textual_metrics.ipynb` and run cells top to bottom.

## Data Layout
- `reports/` contains yearly CSV files named `preds-AFI<YYYY>.csv`.
- `textual-metrics/outputs/` stores generated artifacts from notebook runs.

## Notes
- Use relative paths inside the notebook so it runs from the repo root.
- Keep new report files in `reports/` and follow the existing naming pattern.
