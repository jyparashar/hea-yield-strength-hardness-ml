# Measure hardness first: ML prediction of HEA yield strength

Code for the paper:
**"Measure hardness first: using cheap hardness data to improve machine-learning predictions of high-entropy alloy yield strength under honest validation"**
Ajay Raj Parashar (Department of Computer Science & Engineering, Hindustan College of Science & Technology, Farah, Mathura, India), [Journal, year]. DOI: [add after publication]

## What is in this repository

| Notebook | What it does | Paper section |
|---|---|---|
| `01_data_cleaning_and_baseline.ipynb` | Downloads and cleans the MPEA dataset, computes descriptors, compares random vs. grouped cross-validation | 2.1-2.5, 3.1 |
| `02_hardness_to_strength_transfer.ipynb` | Compares five ways of using hardness data (M0-M4) with repeated grouped cross-validation | 2.6, 3.2 |
| `03_uncertainty.ipynb` | Bootstrap-ensemble uncertainty, calibration, noise floor of the data | 2.7, 3.3 |
| `04_interpretation_and_paper_figures.ipynb` | SHAP interpretation; collects all paper figures and captions | 2.8, 3.4 |

Folders: `figures/` (all figures), `results/` (all result tables as CSV), `paper_figures/` (figures numbered as in the paper).

## How to reproduce

```bash
pip install -r requirements.txt
jupyter notebook
```
Run the notebooks in order (01 to 04), each with *Restart & Run All*. Notebook 1 downloads the dataset into `data/`. Total run time is about 5 minutes on a laptop; no GPU is needed.

## Data

This work uses the MPEA dataset by Borg et al., *Scientific Data* 7, 430 (2020), available at https://github.com/CitrineInformatics/MPEA_dataset under the Apache 2.0 licence. The dataset is not copied into this repository; the notebooks download it.

## Citation

If you use this code, please cite the paper above and this software archive (see `CITATION.cff`).

## Contact

Ajay Raj Parashar, jyparashar@gmail.com

## Licence

Code: MIT licence (see `LICENSE`).
