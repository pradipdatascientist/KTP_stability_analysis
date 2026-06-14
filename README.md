# Data Analysis

This repository contains a Jupyter notebook analysis for the accelerated stability exercise.

## Contents

- `notebooks/KTP_stability_analysis.ipynb` — full analysis notebook with comments, plots and modelling.
- `outputs/` — generated plot images from the notebook.
- `requirements.txt` — Python packages needed to run the notebook.
- `data/` — placeholder directory for the supplied dataset. 

## How to run

1. Create and activate a Python environment:

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Place the supplied Excel workbook in the `data/` folder using this filename:

```text
data/KTP_task_datasets.xls
```

Alternatively, edit the `DATA_PATH` variable near the top of the notebook.

4. Launch Jupyter:

```bash
jupyter lab
```

5. Open and run:

```text
notebooks/KTP_stability_analysis.ipynb
```

## Notes

- The notebook uses transparent exploratory analysis and simple OLS models to support formulation comparison and discuss limitations.
