# materials-ml-examples

Two polished examples for band-gap prediction from Materials Project data.

- `01_tabular_baselines_bandgap.ipynb` — matminer features → Ridge/XGB; IID + OOD, parity plots.
- `02_ann_bandgap.ipynb` — ANN (PyTorch) vs tree ensembles; leak-free CV; saved figures.

## Repro
```bash
conda env create -f environment.yml
conda activate thermo-ml
export MP_API_KEY="VzNVmBMga05iZbWxZz3XFrV74z9ih3jE"
