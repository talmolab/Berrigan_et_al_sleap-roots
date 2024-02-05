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

## Figure 8 
### Efficient models require fewer labels for accurate predictions and facilitate diverse training sets.

**Notebook:** `figure-8\figure_8_sample_efficiency.ipynb`

**Data:**
-`figure-8\sample_efficiency_summary.csv`

**Outputs:**
- Plot showing 90% percentile error vs. number of labeled frame for training per dataset.
- Plot showing number of labeled frames required in training set for model to plateau to within 3 mm of best.
- CSV file of number of labeled frames and 90% percentile error value for each trained model that reached plateau.

