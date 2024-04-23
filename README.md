# Impact of blood glucose levels and glucose variability on the mortality rate of sepsis patients in the intensive care unit (ICU)

#### COMP90089: Machine Learning Applications for Health.  
#### Semester 2, 2023
#### University of Melbourne 
#### Group - 1

## Description
This project focuses on studying the potential link between blood glucose levels and patient mortality in the context of sepsis within the ICU. Sepsis is a severe condition triggered by the body's response to infection, which can lead to organ failure and has a significant impact on global healthcare.

The primary objective of this project is to investigate the correlation between blood glucose levels and glucose variability in sepsis patients during their first 24 hours of ICU admission. We aim to develop predictive models that can help identify patients at the highest risk of mortality, particularly within this crucial timeframe.

## Data Source:
We utilize the MIMIC-IV database `https://physionet.org/content/mimiciv/2.2/`, a public healthcare records database containing ICU patient information from the Beth Israel Deaconess Medical Center in Boston, Massachusetts. Access to patient data is obtained following legal and ethical protocols and approvals.

## File Structure
`patients_cohort.ipynb`: This Jupyter notebook contains the code for extraction of the patient cohort.
`preprocessing.ipynb`: This Jupyter notebook pre-process the row data resulted from `patients_cohort.ipynb`.
`Visualizations.ipynb`: This Jupyter notebook visualise the data distribution and feature Correlation.
`nn.ipynb`: This Jupyter notebook contain the code for Neural Network.
`dev.ipynb`: This Jupyter notebook contain the code for all the other models used in the project.
`requirements.txt`: List of Python dependencies and their versions used in this project.
`final_cohort_dod.csv`: Dataset containing patient cohort before pre-process.
`final_cohort_dod_cleaned.csv`: Dataset containing patient cohort after pre-process.

## Prerequisites

- Python 3.10
- Standard hardware configurations are sufficient for running this notebook.

## Instructions

### For Mac
1. Clone this repository to your drive.

2. Run the Jupyter notebook in below order:
    `jupyter notebook patients_cohort.ipynb`
    Note: This will write the `final_cohort_dod.csv` in to your drive location `/content/`. copy that csv file in to the code directory.
    `jupyter notebook preprocessing.ipynb`
    Note: This will write the `final_cohort_dod_cleaned.csv` in to your drive location `/content/`. copy that csv file in to the code directory.
    `jupyter notebook Visualizations.ipynb`
    `jupyter notebook nn.ipynb`
    `jupyter notebook dev.ipynb`
3. Execute each cell in the notebook to perform the analysis.
    


