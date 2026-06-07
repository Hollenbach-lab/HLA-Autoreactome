# HLA-Autoreactome

Code to reproduce the figures from the paper:

**"HLA class II genotype shapes the healthy human autoreactome"**

## Setup

Create the conda environment using:

```bash
conda env create -f peptidome.yml
conda activate peptidome
```

## Data Preparation

Before running the notebook, unzip:

```text
data/pairseq_results_bin.zip
```

to:

```text
data/pairseq_results_bin.csv
```

and place the CSV file in the `data/` directory.

## Reproducing Figures

Run the notebook:

```text
Figure_Notebook.ipynb
```

to reproduce the figures presented in the manuscript.

## Questions?
Send an email to rayo.suseno@ucsf.edu for any questions related to this repository!