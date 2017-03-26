# Predicting-Ventilator-Associated-Events

1. Synopsis
Predicting Ventilator Associated  Event (VAE) incidence rate, using categorical predictors such as Type of Unit Admitted (MICU, CCU, NCCU etc), Size of Hospital (Large, Medium, and Small) and Location Setting of Hospital (Rural, Urban, Suburban) by applying multiple linear regression in R studio.
 	
2. Motivation
Ventilator is a medical device which provides aid for breathing when a patient is unable to breathe by his own, so basically we are predicting whether the patient will be in such a stage. If we will know this situation well in advance then definitely some work can be done to prevent this situation. 

3. Download and Installation of R studio
One can download R studio from the below link
https://www.rstudio.com/products/rstudio/download/

4. Packages used for this project
ISLR     1.0
         LEAP     0.2
 RColorBrewer   1.1-2
        RGtk2 2.20.31
         Rcpp  0.12.7
        akima  0.5-12
       arules   1.5-0
   assertthat     0.1
   colorspace   1.3-0
    dichromat   2.0-0
       digest  0.6.10
      foreach   1.4.3
          gam    1.14
        gdata  2.17.0
      ggplot2   2.2.0
       glmnet   2.0-5
      gmodels  2.16.2
       gtable   0.2.0
       gtools   3.5.0
    iterators   1.0.8
     labeling     0.3
     lazyeval   0.2.0
        leaps     2.9
     magrittr     1.5
      munsell   0.4.3
          pls   2.5-0
         plyr   1.8.4
       rattle   4.1.0
     reshape2   1.4.2
       scales   0.4.1
           sp   1.2-3
      stringi   1.1.2
      stringr   1.1.0
       tibble     1.2
      Package Version
         ISLR     1.0
         LEAP     0.2
 RColorBrewer   1.1-2
        RGtk2 2.20.31
         Rcpp  0.12.7
        akima  0.5-12
       arules   1.5-0
   assertthat     0.1
   colorspace   1.3-0
    dichromat   2.0-0
       digest  0.6.10
      foreach   1.4.3
          gam    1.14
        gdata  2.17.0
      ggplot2   2.2.0
       glmnet   2.0-5
      gmodels  2.16.2
       gtable   0.2.0
       gtools   3.5.0
    iterators   1.0.8
     labeling     0.3
     lazyeval   0.2.0
        leaps     2.9
     magrittr     1.5
      munsell   0.4.3
          pls   2.5-0
         plyr   1.8.4
       rattle   4.1.0
     reshape2   1.4.2
       scales   0.4.1
           sp   1.2-3
      stringi   1.1.2
      stringr   1.1.0
       tibble     1.2
 
4. Data Set Location:
The data is de-identified data collected for a grant funded project for The Armstrong Institute at Johns Hopkins University and is not available online. The data is collected from 198 different care units across 38 states in the United states over 3 cohort cycles.
Link: https://drive.google.com/open?id=1JYpm2pEJuVxppQ8M6zQLK_graGAubH4Vib78Zbaq9rk
 
5. Number of records (n): 5165
 
6. Number of Attributes (p): 13
 
7. Response Variable: VAE Incidence rate is the response variable
                         	VAE Incidence rate is calculated as follows:
               	VAE =Sum of (VAC, IVAC, and VAP) / No of days on the ventilator
8. Predictor Variables:
1.    Size of the hospital (small, medium, large)
2.    Type of Community (rural, urban, suburban)
3.    Type of Care Unit
