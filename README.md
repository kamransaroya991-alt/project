# Structural network plots

Data preparation, calculations, experiments, figures and interpretation for **Structural network plots: a scalable visual summary for large graph data**, in a single executed notebook (68 cells).

## Contents

- `Structural_Network_Plots_Practical_Notebook.ipynb` — complete analytical code with executed outputs.
- `data/` — the five archived graph inputs (`karate_club`, `les_miserables`, `southern_women`, `florentine_families`, `celegansneural`) plus `datasets.json` (source register) and `SOURCE_NOTICES.md`.
- `results/` — 41 files: measurements, numerical checks, prediction records, experiment tables, `environment.json` (recorded run environment) and `figure_register.json`.
- `figures/` — all 42 analytical figures at exported resolution.
- `requirements.txt` — pinned dependencies.

## Execution

Recorded environment: Python 3.13.5 (see `results/environment.json`), random seed `20260906`. Keep these directories beside the notebook, then:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

On Windows, use the activation command for the selected shell. Open the notebook, restart the kernel and run all cells in order. Or headless:

```bash
jupyter nbconvert --to notebook --execute --inplace Structural_Network_Plots_Practical_Notebook.ipynb --ExecutePreprocessor.timeout=900
```

Copy the notebook first to preserve the delivered timing measurements. The larger-graph and force-layout experiments are computationally heavier than the earlier cells. No data download is needed; dependency installation requires internet access. Existing outputs can be read without execution.
