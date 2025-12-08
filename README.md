# A Diffusion-Based Framework for High-Resolution Precipitation Forecasting over CONUS
This repository contains the code and experimental framework accompanying the paper:

Vicens-Miquel, M., McGovern, A., Hill, A. J., Foufoula-Georgiou, E., Guilloteau, C., & Shen, S. S. P.  
*“A Diffusion-Based Framework for High-Resolution Precipitation Forecasting over CONUS.”*  
*Artificial Intelligence for the Earth Systems (submitted, pending review).*  
📄 [Preprint available on arXiv](https://arxiv.org/abs/XXXX.XXXXX)

---

## Abstract
This study introduces a diffusion-based deep learning framework for 1–12 hour precipitation forecasting over the CONUS at 1 km resolution.  
The model leverages HRRR forecasts and MRMS observations through a residual learning approach, improving both the spatial and intensity representation of rainfall.  
Comprehensive evaluations—spanning pixel-wise, and spatiostatistical metrics—demonstrate enhanced skill compared to the HRRR baseline, particularly in capturing small scale precipitation structures.

---

## Repository Content

- **`/src/`** – Core model and training scripts (TensorFlow implementation)  
- **`/evaluation/`** – Evaluation pipeline for pixel-wise, bootstrap, and spatiostatistical metrics  
- **`/data_preprocessing/`** – Regridding, normalization, and dataset preparation scripts  
- **`/figures/`** – Example visualizations and figures from the paper  
- **`requirements.txt`** – Required Python packages and dependencies  

---

## Dependencies

This project was developed and tested with:
- Python ≥ 3.10  
- TensorFlow ≥ 2.14  
- xarray, xESMF, NumPy, Matplotlib, SciPy, tqdm  

---

## Citation

If you use this code or refer to the methodology, please cite:

**APA Style:**

> Vicens-Miquel, M., McGovern, A., Hill, A. J., Foufoula-Georgiou, E., Guilloteau, C., & Shen, S. S. P. (2025).  
> *A Diffusion-Based Framework for High-Resolution Precipitation Forecasting over CONUS.*  
> *Artificial Intelligence for the Earth Systems.* (Submitted, pending review).

**LaTeX:**

```bibtex
@article{vicensmiquel2025diffusion,
  title={A Diffusion-Based Framework for High-Resolution Precipitation Forecasting over CONUS},
  author={Vicens-Miquel, Marina and McGovern, Amy and Hill, Aaron J. and Foufoula-Georgiou, Efi and Guilloteau, Clement and Shen, Samuel S. P.},
  journal={Artificial Intelligence for the Earth Systems},
  year={2025},
  note={Submitted, pending review},
  eprint={arXiv:XXXX.XXXXX}
}
