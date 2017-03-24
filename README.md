# Predicting-Ventilator-Associated-Events

Predicting relation between Ventilator Associated  Event (VAE) incidence rate and categorical data such as type of unit admitted, size and location setting of the Hospital.
 	
Problem Statement?
To Predict VAE (Ventilator Associated Event) Incident Rate given the
○      Hospital setting (rural, urban, suburban)
○      The unit in which the patient is admitted (ICU, SICU, MICU & CCU)
○      The number of ventilator days
○      Size of the hospital (small, medium or large based on the number of beds) by identifying the relationship between them and VAE rate in a hospital.
 
Note : Ventilator Associated Events (VAE), include Ventilator Associated Conditions(VAC), Infection related to Ventilator Associated Complication(IVAC) and Ventilator Associated Pneumonia (VAP).
 
2. Data Set Location:
The data is de-identified data collected for a grant funded project for The Armstrong Institute at Johns Hopkins University and is not available online. The data is collected from 198 different care units across 38 states in the United states over 3 cohort cycles.
Link: https://drive.google.com/open?id=1JYpm2pEJuVxppQ8M6zQLK_graGAubH4Vib78Zbaq9rk
 
3. Number of records (n): 5165
 
4. Number of Attributes (p): 13
 
5. Response Variable: VAE Incidence rate is the response variable
                         	VAE Incidence rate is calculated as follows:
               	VAE =Sum of (VAC, IVAC, and VAP) / No of days on the ventilator
6. Predictor Variables:
1.    Size of the hospital (small, medium, large)
2.    Type of Community (rural, urban, suburban)
3.    Type of Care Unit
