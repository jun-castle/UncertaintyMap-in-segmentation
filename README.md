### UQ for Digital Retinal Images for Vessel Extraction (DRIVE) 

## (requires datasets) 

Please see `Re.UQ_DRIVE_stochastic_sample_200.ipynb`.

Visualize a map of quantified uncertainty decomposed into 'Aleatoric' and 'Epistemic' with Bayesian neural network.

## Files

- `models.py` contains the scripts for the Bayesian dropout and network architectures (2D U-Net).
- `utils.py` contains functions for the prediction and the preprocessing procedures.

## References

- [DRIVE website](https://www.isi.uu.nl/Research/Databases/DRIVE/)

- J.J. Staal, M.D. Abramoff, M. Niemeijer, M.A. Viergever, B. van Ginneken, "Ridge based vessel segmentation in color images of the retina", IEEE Transactions on Medical Imaging, 2004, vol. 23, pp. 501-509.

- Kwon, Y., Won, J. H., Kim, B. J., & Paik, M. C., "Uncertainty quantification using Bayesian neural networks in classification: Application to biomedical image segmentation". Computational Statistics & Data Analysis, 2020, 142, 106816.

January, 2024.