# Berrigan_et_al_sleap-roots
This repository contains the code for figures and analyses presented in Berrigan et al. *Fast and efficient root phenotyping via pose estimation*.

## Environment Setup
Before running the analyses, set up the conda environment using the provided `env.yaml` file. This ensures that you have all the necessary dependencies installed. Execute the following commands in your terminal:

```bash
conda env create -f env.yaml
conda activate berrigan_et_al
```

## Figure 5
### SLEAP models accurately located root landmarks in 4 species and 3 classes of roots.

**Notebook:** `figure-5/figure_5_error_summary.ipynb`

**Data:**
- `figure-5/average_root_lengths.csv`
- `figure-5/plantwise_testsets_metrics.csv`

**Outputs:**
- Plots showing median localization error as a percentage of average root length.
- CSV files containing numerical metrics for each model.

