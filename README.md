# BI453-FYP
Record of all scripts and files used for analysis and generating results
# Breast Cancer Relapse Prediction using Machine Learning

This project uses machine learning to predict relapse-free survival (RFS) in breast cancer patients using clinical data, mRNA expression, and DNA methylation profiles from the METABRIC dataset.

## What This Project Does

- Predicts breast cancer relapse using real patient data
- Compares models trained on:
  - Clinical data only
  - mRNA data only
  - DNA methylation only
  - All combinations of the above
- Uses PyCaret for easy model comparison and evaluation

## Data

The data comes from the **METABRIC** dataset, available publicly on [cBioPortal](https://www.cbioportal.org/study/summary?id=brca_metabric).

> ⚠️ This project does **not** include the raw METABRIC data — please download it directly from cBioPortal if needed.
>
> full meethylation dataset can be found here along with other starting files: https://drive.google.com/drive/folders/1NDocMMD_BR4sCxZiiqPq7VAfiWcnILas?usp=drive_link

## How to Use This Project

1. Make sure you have Python installed.
2. Install required Python packages by running; pip install -r requirements.txt
3. start files are withing repository; files.zip
