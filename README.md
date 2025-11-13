# Adaptive-Block-Adjustment-Framework

This is an offical implementation of 《Adaptive Transformer Dual Correction Method for Low-Accuray DEMs with Higher Spatial Resolution》.

## Key Designs

![alt text](https://github.com/FloudXX/Adaptive-Block-Adjustment-Framework/blob/main/pic/main_process.png)

## Getting Started

1. Install requirements. ```pip install -r requirements.txt```

2. Prepare data. The image data used in the paper and the intermediate products during the processing can all be downloaded from [this link](https://mega.nz/folder/itRHjKaS#xngyOeJ4PDvZvyur6UN2QA).You can also use your own prepared DEM data to complete the experimental process.

3. Run each ipynb file in sequence to process the DEM data. Each program corresponds to the processing steps in the paper, including relative horizontal adjustment（S1）, absolute horizontal adjustment（S2） and vertical adjustment（S3）.

You can adjust the hyperparameters based on your needs . We also provide codes for the baseline models.
