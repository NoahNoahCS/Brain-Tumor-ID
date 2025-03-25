------------------------------------------------------------------------------

## Brain Tumor ID System
=========================

### Executive Summary

... As cancer rates rise it is crucial increase hospital efficiency if we want to continue to give quality care to our most at-risk patients. The project will help diagnose brain tumors given genetic information. 
... The project consists of two parts. 
    1. Using genetic data, the information will be used to predict what kind of cancer a patient has. In our current dataset the two types of tumor that are being predicted are Glioblastoma Multiforme (GBM) and Low Grade Glioma (LGG)  
    2. A recommendation model will provide a suggestion for a treatment plan for the patient given their patient info, past treatment info, and the specific type of tumor.
... Key takeaways

### Demo

... Show your work:
...     Data visualizations
...     Interactive demo (e.g., `streamlit` app)
...     Short video of users trying out the solution


### Methodology

... High-level diagrams of entire process:
...     Genetic Data 
        1. Data Acquisition and Preprocessing
        2. Research / Domain Knowledge
        3. Feature Engineering
        4. Model Training
            a. Logistic Regression
            b. Decision Tree
            c. K Nearest Neighbors
        5. Model Evaluation

...     Treatment Data
        1. Data Acquisition and Preprocessing
        2. Model Choice
        3. Model Training
        4. Model Evaluation
        
...     various modelling directions
...     various prototyping directions


### Organization

#### Repository 

* `data` 
    - https://docs.google.com/document/d/1YxfU2WQrP9JgYS0MiYoAdp6zUTAPDMq4n6r_pMbP9oI/edit?usp=sharing

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - contains all final notebooks involved in the project

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
    https://docs.google.com/document/d/1YxfU2WQrP9JgYS0MiYoAdp6zUTAPDMq4n6r_pMbP9oI/edit?usp=sharing

### Credits & References

References
    - 
