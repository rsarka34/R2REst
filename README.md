# R2REst

**R2Rest: A Novel Deep Learning Framework for Estimating Respiration Rate from Respiratory Sounds**

**Authors: Soubhagya Ranjan Hota&dagger;, Arka Roy&dagger;, and Udit Satija** (&dagger; means equally contributed in the paper)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rsarka34/R2REst/blob/main/model/TBDB/R2REst_TBDB_Git.ipynb)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rsarka34/R2REst/blob/main/model/TBCS/R2REst_TBCS_Git.ipynb)
[![Paper Link](https://img.shields.io/badge/Preprint-TechRixv-red)](https://www.techrxiv.org/doi/full/10.36227/techrxiv.174318053.37913618) 


# Abstract
<p align="justify">
Non-invasive respiratory activity assessment including airflow signal (AF)-derived vital extraction such as respiration rate (RR), tidal volume, peak expiratory rate, etc., and adventitious breathing event detection, are emerging research areas in continuous health monitoring. Recent studies have demonstrated a strong pathological correlation between AFs and respiratory sounds (RSs). In this research, we present a unified deep learning framework, namely R2REst, for RR estimation by synthesizing equivalent electrical impedance tomography (EIT)-based AFs from RSs. The proposed framework comprises four major stages: pre-processing, mel spectrogram generation, mel spectrogram-vision transformer-based AF prediction, and lastly, RR estimation by analyzing the frequency spectrum of the predicted AF signal. Experimental results on the RSs from BRACETS dataset show that the proposed framework exceeds existing works on RR estimation which utilize either RSs or other bio-acoustic modalities, by obtaining a mean square error (MSE) and mean absolute error (MAE) of 0.001, 0.003 and 0.010, 0.016 (in breaths per minute (BPM)) for tidal breathing followed by deep breathing (TBDB) and cough-speech (TBCS) induced cases. 
</p>

# Methodology
![R2REst_blockdiag](https://github.com/user-attachments/assets/6e2d9ea2-6586-4e20-bf4a-43f3e14a5f4b)

# Dataset
**BRACETS Dataset:**  [![Paper Link](https://img.shields.io/badge/BRACETS%20Data-Mendeley%20Data-red)](https://data.mendeley.com/datasets/f43c7snks5/1)  
<p align="center">
  <img width="893" alt="Screenshot 2025-04-24 at 6 16 41 PM" src="https://github.com/user-attachments/assets/cdcd6982-0113-44bf-b7de-472f42ace1a5" />
</p>

# Results
<p align="center">
<img width="800" alt="Screenshot 2025-04-25 at 11 52 21 AM" src="https://github.com/user-attachments/assets/2d319fc6-04fd-4d50-a4b8-3da424a73d65" />
</p>

# Performance

<p align="center">
<img width="803" alt="Screenshot 2025-04-25 at 12 02 59 PM" src="https://github.com/user-attachments/assets/18975e46-6b13-4645-90ca-46c3ef3885c9" />
</p>

# Cite as
Soubhagya Ranjan Hota, Arka Roy, Udit Satija. ``R2REst: A Unified Deep Learning Framework for Estimating Respiration Rate from Respiratory Sounds". *TechRxiv*. March 28, 2025.
DOI: 10.36227/techrxiv.174318053.37913618/v1

```bibtex
@article{hota2025r2rest,
  title={R2REst: A Unified Deep Learning Framework for Estimating Respiration Rate from Respiratory Sounds},
  author={Hota, Soubhagya Ranjan and Roy, Arka and Satija, Udit},
  journal={Authorea Preprints},
  year={2025},
  publisher={Authorea}
}
