# Assessment of Class Imbalance Techniques in Health-Related Classification Problems

## Overview

This repository is associated with an assessment of class imbalance techniques in health-related classification problems, using stroke-related data as an applied example. While analyzing health data is important for improving health outcomes, class imbalance in datasets poses major challenges to machine learning classification models. This work, therefore, considers the class imbalance problem in stroke prediction using models such as K‐nearest neighbors, support vector machine, logistic regression, random forest, and decision tree. This work balances the stroke dataset, thereby enhancing model performance, through various oversampling strategies: random oversampling (RO), ADASYN, SMOTE, and SMOTE–Tomek. Compared to the results of the imbalanced dataset, all applied oversampling techniques enhanced the correct classification of stroke events by the ML model. Among these, RO–SVM with RBF kernel was the best in terms of sensitivity, specificity, G‐mean, F1‐score, and accuracy values, offering the highest results with respective values of 89.87%, 94.91%, 92.36%, 89.64%, and 89.87%. After applying oversampling techniques, all the machine learning classifications were good enough to classify stroke status, especially for the minority class. This study has highlighted the importance of class imbalance issues in health datasets. Precise detection of instances of minority classes can be enhanced considerably by employing classification models with the implementation of hybrid strategies to effectively solve class imbalance issues, which, in turn, will help improve healthcare outcomes. Further research in integrating more advanced deep learning techniques into other health datasets with imbalances is encouraged to further validate or refine class imbalance approaches, as effective handling of imbalanced classes can substantially promote predictive model performance in the analysis of healthcare.

## Repository

- **Repository name:** `Stroke`
- **Repository type:** Health classification data repository
- **Repository link:** https://github.com/Agyemang1z/Stroke
- **Primary author:** Edmund Fosu Agyemang
- **Academic identifier:** ORCID: https://orcid.org/0000-0001-8124-4493

## Repository Contents

The public repository listing identifies the following files:

- `stroke.csv`
-  `stroke.ipynb`

## Research Objectives

- Provide data resources for studying class imbalance in health-related prediction.
- Support evaluation of oversampling and imbalance-aware classification methods.
- Encourage transparent comparison of model performance before and after data balancing.
- Document the repository clearly so that analytical code can be added and reproduced.

## Analytical Workflow

1. Load `stroke.csv` and inspect missingness, variable types, and class distribution.
2. Define the stroke classification outcome and candidate predictors.
3. Train baseline classifiers on the imbalanced dataset.
4. Apply oversampling or hybrid balancing methods where appropriate.
5. Evaluate models using metrics appropriate for imbalanced data, including sensitivity, specificity, F1 score, ROC-AUC, PR-AUC, and balanced accuracy.
6. Compare pre-balancing and post-balancing performance.

## Software Requirements

Recommended software and packages include:

- Python 3.10 or later if using notebooks
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib

## Reproducibility Guide

Run the project from a clean working directory. The following commands provide a suggested starting point:

```bash
git clone https://github.com/Agyemang1z/Stroke.git
cd Stroke
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install pandas numpy scikit-learn imbalanced-learn matplotlib jupyter
# Add the analysis notebook or script, then run it from this directory.
```

If file names include spaces, keep quotation marks around the file name when launching notebooks or scripts from the terminal.

## Expected Outputs

- Class distribution summaries
- Imbalance-aware classification metrics
- Pre-balancing and post-balancing model comparisons
- Reproducible tables and figures once analysis code is added

## Data Availability and Responsible Use

The data and code are provided for scholarly, educational, and reproducibility purposes. Users should verify the original data source, data license, and any use restrictions before redistribution or secondary analysis. When the dataset contains human, health, financial, or election-related information, results should be interpreted responsibly and reported with appropriate methodological caution.

## Suggested Citation

Agyemang, E. F., Mensah, J. A., Nyarko, E., Arku, D., Mbeah-Baiden, B., Opoku, E., & Noye Nortey, E. N. (2025). *Addressing class imbalance problem in health data classification: Practical application from an oversampling viewpoint.* Applied Computational Intelligence and Soft Computing, 2025(1), 1013769. [Source code and data]. GitHub. https://github.com/Agyemang1z/Stroke

If this repository supports a manuscript, replace the citation above with the final article citation after publication. For stronger academic referencing, consider creating a GitHub release and archiving the release on Zenodo to obtain a DOI.

## Keywords

Stroke prediction, Class imbalance, Oversampling, Health analytics, Machine learning, Classification

## Disclaimer

This repository is intended to support reproducible research. The code and outputs should not be used as a substitute for professional clinical, financial, legal, electoral, or policy judgment.
