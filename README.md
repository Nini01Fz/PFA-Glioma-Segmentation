# Glioma Segmentation – BraTS2019 & BraTS-Africa

## Project Overview
This project investigates the generalization of deep learning models for brain glioma segmentation using MRI data, with a focus on the BraTS-Africa dataset.

The objective is to evaluate how models trained on different datasets perform when applied to African MRI data.

## Objectives
- Explore and analyze brain MRI datasets.
- Preprocess MRI images and segmentation masks.
- Develop and evaluate 3D U-Net-based segmentation models.
- Compare models trained on BraTS2019 and BraTS-Africa.
- Investigate cross-dataset generalization and fine-tuning.
- Analyze model calibration and predictive uncertainty.

## Datasets
- **BraTS2019:** Used for baseline model training.
- **BraTS-Africa:** Used for training, evaluation, and cross-dataset analysis.

The BraTS-Africa data includes four MRI modalities:
- T1n
- T1c
- T2w
- T2f

## Methodology
1. Dataset exploration and quality checks.
2. MRI preprocessing and Z-score normalization.
3. Patient-level training, validation, and testing split.
4. 3D patch extraction.
5. 3D U-Net model training.
6. Model comparison:
   - BraTS2019 Baseline
   - BraTS-Africa From Scratch
   - BraTS2019 + BraTS-Africa Fine-Tuning
7. Calibration and uncertainty analysis.
8. Statistical evaluation of results.

## Evaluation Metrics
- Dice Score (WT, TC, ET)
- Expected Calibration Error (ECE)
- Brier Score
- Predictive Entropy
- Statistical significance testing

## Technologies
- Python
- PyTorch
- NumPy
- Pandas
- NiBabel
- Matplotlib
- Google Colab
- Jupyter Notebook

## Repository Contents
- `PFA_Glioma_Segmentation.ipynb`: Main notebook containing the project workflow, experiments, model evaluation, and analysis.

## How to Run
1. Open the notebook using Google Colab.
2. Mount Google Drive.
3. Configure the dataset path according to your environment.
4. Install the required dependencies.
5. Execute the notebook cells in order.

**Note:** The MRI datasets are not included in this repository. Access to the datasets must be obtained separately.

## Academic Project
Master's Program – Information Systems & Artificial Intelligence (SIIA)

