# Age-Dependent microRNA Associations with Incident Heart Failure

This repository contains the analysis code for investigating age-dependent associations between circulating microRNAs (miRNAs) and incident heart failure in the Rotterdam Study.

The analyses evaluate associations between circulating miRNAs and incident heart failure using Cox proportional hazards regression and investigate whether these associations vary with age. Additional analyses include SHAP-based assessment of age-dependent miRNA effects and network/pathway analyses.

## Repository Structure

The analysis workflow is organized into four Jupyter notebooks:

- `01_descriptive_statistics.ipynb`  
  Data preparation and descriptive statistics of the study population.

- `02_cox_regression_and_interaction_analysis.ipynb`  
  Cox proportional hazards regression analyses of miRNAs and incident heart failure, including miRNA × age interaction analyses.

- `03_shap_age_interaction_analysis.ipynb`  
  SHAP-based analysis and visualization of age-dependent miRNA associations.

- `04_network_analysis.ipynb`  
  Network and pathway analyses of miRNAs showing evidence of age-dependent associations with incident heart failure.

## Analysis Workflow

The notebooks are numbered according to the main analysis workflow and should generally be run in the following order:

1. Descriptive statistics
2. Cox regression and age-interaction analysis
3. SHAP age-interaction analysis
4. Network analysis

## Software

The analyses were performed using R and Python within Jupyter Notebook.

The main statistical and machine-learning methods include:

- Cox proportional hazards regression
- Multiple-testing correction using false discovery rate (FDR)
- Gradient-boosted decision trees
- SHAP (SHapley Additive exPlanations)
- miRNA target and pathway/network analysis

Package and session information used for individual analyses is provided within the corresponding notebooks.

## Data Availability

The individual-level Rotterdam Study data used in these analyses are not included in this repository due to participant privacy and data-access restrictions.

The analysis code is provided to support transparency and reproducibility of the study methodology.

## Citation

If you use this code or methodology, please cite the corresponding publication.

Publication details will be added upon publication.

## Contact

**Ali Farzaneh**  
a.farzanehalanagh@erasmusmc.nl
Erasmus MC, University Medical Center Rotterdam  
Department of Epidemiology
