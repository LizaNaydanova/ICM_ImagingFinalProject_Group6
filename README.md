# ICM_ImagingFinalProject_Group6
**Group Members**
- Aseem Jain (ajain36@jhu.edu)
- Yikun Li (yli538@jhu.edu)
- Liza Naydanova (enaydan1@jhu.edu)
- Naeiri Shahmirzaeian Savarani (nshahmi1@jhu.edu)

**Contributions**
Aseem: Literature review 
Yikun: Created MATLAB heatmap plots of barcodes for the ADNI and MNI datasets and calculated barcode for MNI Atlas patient.
Liza: Calculated barcodes for ADNI dataset and performed statistical analysis of data
Naeiri: Backround information research and put together PowerPoint


## Final Project for ICM: Imaging (Group 6)

**Disease:** Alzheimer's disease (ADNI dataset)

**Brain region:** Limbic system

## Code
### Barcodes and Statistical Analysis
All data cleaning, barcode computations (for both the patients in the ADNI dataset as well as the MNI Atlas patient), and statistical analysis (Yuen test) comparing volume means of healthy and AD/MCI patients are in ```Code/statistical_computations.ipynb```. In order to run this file, change the definition of the ```data_directory``` variable to the directory where the ```ADNI_ICM_random200.xlsx``` and ```MNI_T1L5.xlsx``` datasets are located. The barcodes for the ADNI dataset and the MNI Atlas patient will be saved in 2 files within ```data_directory```. 

The table containing all of the patient barcodes (for structures in the limbic system) is in ```ADNI_zscores.xlsx``` and the table containing the barcode for the MNI Atlas patient is in ```MNI_zscores.xlsx```.

### Plotting
Barcode plots (both the subset of the dataset and the full dataset) are in ```heatmap_plots.mlx```. In order to run it, change the definition of the ```data_directory``` variable to the directory where the ```ADNI_zscores.xlsx``` and ```MNI_zscores.xlsx``` datasets are located.

## Data
- ```ADNI_ICM_random200.xlsx```: original dataset
- ```ROI_fullname.xlsx```: excel file with expanded names of all abbreviations used in ```ADNI_ICM_random200.xlsx```
- ```MNI_286Labels_corrected_stats.txt```: original file with all data from the MNI Atlas segmentation
- ```MNI_T1L5.xlsx```: excel file with only T1L5 data from the MNI Atlas segmentation
- ```ADNI_zscores.xlsx```: The table containing all of the patient barcodes (for structures in the limbic system)
- ```MNI_zscores.xlsx```: The table containing the barcode for the patient from the MNI Atlas (for structures in the limbic system)

## Final Presentation
Google slide deck for the final presentation: [link](https://docs.google.com/presentation/d/1wEt03VnvqqzIaZoA0U72KR32_NWEQ3K0d5-0IDo6RJs/edit?usp=sharing)
