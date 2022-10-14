# ICM_ImagingFinalProject_Group6
**Group Members**
- Aseem Jain (ajain36@jhu.edu)
- Yikun Li (yli538@jhu.edu)
- Liza Naydanova (enaydan1@jhu.edu)
- Naeiri Shahmirzaeian Savarani (nshahmi1@jhu.edu)

## Final Project for ICM: Imaging (Group 6)

**Disease:** Alzheimer's disease (ADNI dataset)

**Brain region:** Limbic system

## Code
### Barcodes and Statistical Analysis
All data cleaning, barcode computations, and statistical analysis (Yuen test) comparing volume means of healthy and AD/MCI patients are in ```statistical_computations.ipynb```. In order to run this file, change the definition of the ```working_directory``` variable to the directory where the ```ADNI_ICM_random200.xlsx``` dataset is located. 

The table containing all of the patient barcodes (for structures in the limbic system) is in ```zscores_data.xlsx```.

### Plotting
Barcode plots (both the subset of the dataset and the full dataset) are in ```plotting.mlx```. In order to run it, change the definition of the ```folder``` variable to the directory where the ```zscores_data.xlsx``` dataset is located.

## Data
- ```ADNI_ICM_random200.xlsx```: original dataset
- ```ROI_fullname.xlsx```: excel file with expanded names of all abbreviations used in ```ADNI_ICM_random200.xlsx```
- ```zscores_data.xlsx```: The table containing all of the patient barcodes (for structures in the limbic system)

## Final Presentation
Google slide deck for the final presentation: [link](https://docs.google.com/presentation/d/1wEt03VnvqqzIaZoA0U72KR32_NWEQ3K0d5-0IDo6RJs/edit?usp=sharing)
