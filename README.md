# W1 Zhongli Air Quality Research Project

**Student ID:** 11570016

This repository contains the Week 1 reproducible air-quality analysis using the Zhongli 2025 dataset.

## Project structure

```text
.
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── zhongli_aq_2025.csv
└── notebooks/
    ├── 11570016_W1_Zhongli_AirQuality.ipynb
    └── 11570016_W1_Zhongli_AirQuality.html
```

## Analysis

The notebook includes:

- data inspection
- QA/QC for missing, `-9999`, and negative pollutant values
- descriptive statistics
- an NO2 time-series figure

## Run in JupyterLab

```bash
pip install -r requirements.txt
jupyter lab
```

Open `notebooks/11570016_W1_Zhongli_AirQuality.ipynb` and choose **Run All Cells**.

## Run in Google Colab

Open the notebook in a fresh Colab session and choose **Runtime > Run all**.

If the CSV is not found automatically, the notebook will ask you to upload:

`data/zhongli_aq_2025.csv`

Run all cells and confirm that there are no errors and that the final NO2 figure appears.

## Reproducibility

- JupyterLab-style execution: verified
- Colab uploaded-file path logic: verified in a clean temporary environment
- Actual Google Colab status: confirm in Google Colab before submitting PASS / FAIL
