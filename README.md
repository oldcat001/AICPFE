This is a project for mortality prediction in  patients with CPFE!

Purpose
Combined pulmonary fibrosis and emphysema (CPFE) have an elevated mortality rates without robust prognostic tools. To establish and validate an artificial-intelligence-driven airway and emphysema quantitation (qHRCT) for mortality stratification in patients with CPFE across multicenter cohorts.

Materials and Methods
This prospective multicenter study (ClinicalTrials.gov: NCT04370158) analyzed CPFE patients from three centers with complete follow-ups from diagnosis to death, partitioned into training (70%), validation (15%), and test (15%) cohorts. qHRCT biomarkers included small airway metrics (half-band/FWHM) and emphysema severity (LAA%). An automated machine learning framework tested 100 combinations of 10 survival algorithms to predict all-cause mortality, optimizing through concordance-index (C-index) maximization. Model performance was assessed via time-dependent receiver operating characteristic curve, calibration curves, and decision curve analysis. Restricted cubic spline and piecewise regression determined three risk groups. A clinical web tool was deployed for dynamic risk monitoring.

Results
The study cohort comprised 383 patients with CPFE, including 304 survivors (79.4%) and 79 deceased individuals (20.6%). The survival random forest achieved superior 1-/2-/3-year mortality prediction (test cohort C-indices: 0.84 [95%CI 0.70-0.98], 0.89 [0.77-0.99], 0.83 [0.65-0.99]), outperforming conventional clinical/CT parameters (ΔC-index >0.21, p<0.001). Three risk stratification revealed distinct mortality trajectories (high/intermediate vs. low risk: p<0.001) determined by piecewise regression (likelihood ratio p<0.001). Different risk groups demonstrated diverging pulmonary function decline, emphysema progression, and comorbidity development. The website has been deployed at https://zryh2023.shinyapps.io/AICPFE.

Conclusion
An explainable AI model integrating airway-emphysema enables precision mortality prognostication in CPFE, revealing hidden progression patterns and enabling dynamic intervention monitoring.
