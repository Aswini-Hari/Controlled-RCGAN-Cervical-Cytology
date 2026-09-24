# Controlled Evaluation of RCGAN-Based Synthetic Augmentation for Cervical Cytology Image Classification



This repository contains the experimental and supplementary Jupyter notebooks associated with the research study:



**Controlled Evaluation of RCGAN-Based Synthetic Augmentation for Cervical Cytology Image Classification with Predictive Uncertainty and Grad-CAM Analysis**



The repository provides the computational implementation used to evaluate RCGAN-based synthetic augmentation for cervical cytology image classification, together with predictive uncertainty analysis and Grad-CAM-based visual explanation.



## Repository Contents



The repository contains the following Jupyter notebooks:



### 1. Main Experimental Notebook



`notebooks/Cervix_journal_paper_experimental_code.ipynb`



This notebook contains the primary experimental implementation associated with the study, including:



- Dataset preparation and preprocessing

- ResNet-50-based cervical cytology image classification

- RCGAN-based synthetic image augmentation

- Model training and evaluation

- Locked-test-set performance evaluation

- Classification performance analysis

- Predictive uncertainty analysis

- Grad-CAM-based visual explanation

- Comparative analysis of the experimental models



### 2. Supplementary Notebook



`notebooks/Cervix_journal_Supplementary.ipynb`



This notebook contains supplementary experimental procedures and supporting analyses associated with the main study.



## Datasets



The experimental workflow uses cervical cytology image datasets including:



- Herlev Pap Smear Dataset

- SIPaKMeD Dataset



The original datasets are not redistributed in this repository. Users should obtain the datasets from their respective original sources and configure the corresponding dataset paths before running the notebooks.



## Methodological Components



The computational workflow includes the following major components:



- ResNet-50 fine-tuning for cervical cytology image classification

- RCGAN-based synthetic augmentation

- Comparative evaluation of models trained with and without synthetic augmentation

- Locked-test-set evaluation

- Predictive uncertainty analysis based on classification outputs

- Grad-CAM-based visual explanation

- Supplementary training and validation analyses



## Reproducibility



The notebooks were developed for execution in a Google Colab environment.



To reproduce the experiments:



1. Clone or download this repository.

2. Obtain the required cervical cytology datasets from their original sources.

3. Upload or mount the datasets in the execution environment.

4. Configure the dataset paths used by the notebooks.

5. Install the required Python dependencies.

6. Open the relevant notebook in Google Colab or a compatible Jupyter environment.

7. Execute the notebook cells in their intended sequence.

8. Use a CUDA-enabled GPU when available for computationally intensive model training.



The notebooks may contain environment-specific paths that need to be modified according to the user's local or Google Colab environment.



## Reproducibility Notes



The experimental implementation uses controlled randomization where specified in the notebooks. The relevant experimental sections use a fixed random seed to support reproducibility.



Because training results can depend on software versions, hardware, CUDA configuration, and dataset organization, exact reproduction may require matching the computational environment and dataset preparation procedures used in the original experiments.



## Repository Structure



```text

Controlled-RCGAN-Cervical-Cytology/

│

├── notebooks/

│   ├── Cervix_journal_paper_experimental_code.ipynb

│   └── Cervix_journal_Supplementary.ipynb

│

├── README.md

├── requirements.txt

├── CITATION.cff

├── LICENSE

└── .gitignore

