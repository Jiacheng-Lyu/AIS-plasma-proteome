# AIS-plasma-proteome

This repository includes the code used in AIS-plasma-proteome cohort study.

**Plasma Proteomic Characterization of Adolescent Idiopathic Scoliosis**

Jiacheng Lyu, Tianyuan Zhang, Tao Ji, Zeya Xu, Xiexiang Shao, Lin Bai, Subei Tan, Yaqing Zhang, Junlin Yang, Chen Ding, Wenjun Yang


## Code overview
> The below figure numbers were corresponded to the paper version.

### 1. 1-Cohort design.ipynb
This Jupyter Notebook (with Python 3 kernel) contained the code for cohort design, quality control and data distribution for the AIS plasma proteome study

Output figures:  
* Figure 1B, 1C, 1D, 1E, S1A, S1B, S1C, S1D, S1E, S1F

### 2. 2-Gender proteome comparision.ipynb
This Jupyter Notebook (with Python 3 kernel) contained the code for the proteomic analysis between males and females

Output figures:  
* Figure S3A, S3B, S3C

### 3. 3-WGCNA.ipynb
This Jupyter Notebook (with Python 3 kernel) contained the code for the WGCNA analysis

Output figures:  
*  Figure 2A, 2B, 2C, 2D, 2E, S4A, S4B

### 4. 4-Proteome cluster.ipynb
This Jupyter Notebook (with Python 3 kernel) contained the code for the clustering analysis and its association with disease severity and hormone related biological processes

Output figures:  
* Figure 3A, 3B, 3C, 3D, 3E, 3F, 3G, S5B, S5C

### 5. 5-Cobb proteome undulation.ipynb
This Jupyter Notebook (with Python 3 kernel) contained the code for the proteomic characteristic along with the disease severity

Output figures:  
* Figure 4A, 4B, 4D, 4E, 4F, 4G, S6A, S6B

### 6. 6-Machine learning.ipynb
This Jupyter Notebook (with Python 3 kernel) contained the code for the machine learning model evaluation

Output figures:  
* Figure 5B, 5C, 5D, 5E, S7A, S7B, S7C, S7E, S7F

## Environment requirement
The following package/library versions were used in this study:
* python (version 3.9.15)
* pandas (version 1.5.3)
* numpy (version 1.26.3)
* scipy (version 1.12.0)
* statsmodels (version 0.14.1)
* matplotlib (version 3.7.3)
* seaborn (version 0.11.2)
* scikit-learn (version 1.2.1)
* rpy2 (version 3.5.6)
* gprofiler (version 1.0.0)
* adjustText

## Folders Structure
The files are organised into four folders:
* *code*: contains the python code in the ipython notebook to reproduce all analyses and generate the the figures in this study.
* *document*: which contains all the proteomics and clinical patient informations required to perform the analyses described in the paper.
* *documents*: contains the related annotation files, the Source Data, and the Supplementary Table produced by the code.
* *figure*: contains the related plots produced by the code.
