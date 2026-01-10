# nnU-Net-for-PVS-Segmentation-on-3T-T2w-MRI
Automated segmentation of perivascular spaces in 3T T2-weighted brain MRI using nnU-Net

Trained on 40 whole-brain manual PVS segmentations using 5-fold cross-validation

Input Requirements
Important: T2-weighted images must be preprocessed before inference:

- Registration into MNI space (1mm³ isotropic resolution)
- Brain extraction

