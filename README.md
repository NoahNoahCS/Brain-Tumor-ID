------------------------------------------------------------------------------

------------------------------------------------------------------------------

## Brain Tumor ID System
=========================

### Executive Summary

... As the digitzation and analysis of genetic information is increasingly accessible and efficient, it is important for the medical community to have a robust understanding of the genetic traits of tumors. This will better inform diagnostic procedures, drug manufacturing, health insurance practices, and how to direct future research.
... The primary goal of this project is to explore the genetic differences between two different tyeps of tumors, the Glioblastoma Multiforme, and the Low Grade Glioma. Based on the findings a model will be created to predict what cancer a tumor is between these two types based on user-input information.


### Demo

... Show your work:
...     Data visualizations
...     Model explanation
...     Interactive demo ('streamlit app')


### Methodology

... High-level diagrams of entire process:
...     1. Data Acquisition, EDA, and Preprocessing
        2. Research / Domain Knowledge
        3. Feature Engineering
        4. Address class imbalance (SMOTE / undersampling)
        5. Model Training
            a. Logistic Regression
            b. Decision Tree
            c. K Nearest Neighbors
        6. Model Evaluation
        7. Additional modelling / tuning based on evaluation results


### Organization
... Data
... Notebooks
    1. EDA / Preprocessing
    2. Modelling
... Slides / project presentation

#### Repository 

* `data` 
    - https://genome.ucsc.edu/cgi-bin/hgTables?db=hg38&hgta_group=phenDis&hgta_track=gdcCancer&hgta_table=allCancer&hgta_doSchema=describe+table+schema
    - https://docs.google.com/document/d/1YxfU2WQrP9JgYS0MiYoAdp6zUTAPDMq4n6r_pMbP9oI/edit?usp=sharing

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - Preprocessing notebook
    - Modelling notebook

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset

... 
- The data used is from the TCGA Pan-Cancer Atlas.
- The dataset is accessible via the following link: https://genome.ucsc.edu/cgi-bin/hgTables?
    
### Credits & References

References
    - For additional references, see the following link: https://docs.google.com/document/d/1XN_xRrH_ivsEauc_diLaYyT3xW1zk5_sqR4RfbyeIhQ/edit?usp=sharing
    
