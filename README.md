# CIBMTR---Equity-in-post-HCT-Survival-Predictions

## Description
  Improving survival predictions for allogeneic HCT patients is a vital healthcare challenge. Current predictive models often fall short in addressing disparities related to socioeconomic status, race, and geography. Addressing these gaps is crucial for enhancing patient care, optimizing resource utilization, and rebuilding trust in the healthcare system.

This competition aims to encourage participants to advance predictive modeling by ensuring that survival predictions are both precise and fair for patients across diverse groups. By using synthetic data—which mirrors real-world situations while protecting patient privacy—participants can build and improve models that more effectively consider diverse backgrounds and conditions.

You’re challenged to develop advanced predictive models for allogeneic HCT that enhance both accuracy and fairness in survival predictions. The goal is to address disparities by bridging diverse data sources, refining algorithms, and reducing biases to ensure equitable outcomes for patients across diverse race groups. Your work will help create a more just and effective healthcare environment, ensuring every patient receives the care they deserve.

## Data Visualization

The target variables are:
- **efs** : Event Free Survival. 
    - **efs** is a categorical data that is classified into *Event* & *Censoring*.
- **efs_time** : Time to event-free survival in months
    - **efs_time** is the number months to the event-free survival which allows the doctor to make an assumption regarding the diagnosis.

## Status
The project is in the **Data Visualization** Stage. Where the efs_time is being visulized against the categorical variables using box plots. After completion the visualization will move onto efs.
