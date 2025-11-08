# Adaptive-Block-Adjustment-Framework

This is an offical implementation of Adaptive Transformer Dual Correction Method for Accuracy Improvement of High-resolution Low-Quality DEMs.

## Key Designs

This study proposes an adaptive Transformer dual correction method that jointly optimizes Horizontal Correction (HC) and Vertical Correction (VC) for accuracy enhancement of high-resolution low-quality DEMs. The HC module integrates relative correction based on tie points (TPs) and absolute correction using a Machine Learning (ML) model to improve both local alignment and global positional accuracy, while the VC module employs a single-head Transformer-based DEM Vertical Correction Network (DemVCNet) to extract key terrain features via attention mechanisms for precise elevation error regression.

![alt text](https://github.com/FloudXX/Adaptive-Block-Adjustment-Framework/blob/main/pic/main_process.png)

## Getting Started

1. Install requirements. ```pip install -r requirements.txt```

2. Download  data. The image data used in the paper and the intermediate products during the processing are all stored in [Here](https://mega.nz/folder/itRHjKaS#xngyOeJ4PDvZvyur6UN2QA).

3. Run each ipynb file in sequence to process the DEM data. Each program corresponds to the processing steps in the paper, including relative horizontal adjustment（S1）, absolute horizontal adjustment（S2） and vertical adjustment（S3）.

You can adjust the hyperparameters based on your needs . We also provide codes for the baseline models.
