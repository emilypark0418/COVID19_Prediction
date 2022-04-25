# COVID19_Prediction

- Baseline code for COVID19 infection percentage rate prediction on CT scan slices

## Overview: 

Medical imaging has been shown to be effective in identifying Covid-19 infection. X-rays, CT scans, and ultrasounds are popular Medical Imaging techniques. CT-scan, in particular is useful for identification. The use of CT-scans is not only limited to the detection of COVID-19 cases, but they can also be used for other important tasks such quantifying the infection and monitoring the evolution of the disease.

## Dataset Distribution

The Train set is obtained from 132 CT-scans, from which 128 CT-scans has confirmed to have Covid-19 based on positive (RT-PCR) test. The rest four CT-scans have not any infection type (Healthy). The Val set is obtained from 57 CT-scans, from which 55 CT-scans has confirmed to have Covid-19 based on (RT-PCR) test. The rest two CT-scans have not any infection type (Healthy).

## Evaluation

The evaluation metrics are: Mean Absolute Error (MAE), Pearson Correlation coefficient (PC) and Root Mean Square Error (RMSE). The most important Evaluation Criterion is the MAE. In the event of two or more competitors achieve the same MAE, the PC and the RMSE are considered as the tie-breaker.


## How to Participate

Participation in the Competition: Each team should request to participate in the competition on the CodaLab platform (https://competitions.codalab.org/competitions/35575 (Links to an external site.)) with specifying the team name, members, emails and affiliations. The team informations can be send to: faresbougourzi@gmail.com

## Validation Phase

In the Validation phase, each team should submit the predictions of the validation data as 'predictions.csv' file, which contains the names of the slice images in the first column and the corresponding Covid-19 infection percentage estimation in the second column. This file should be compressed as 'predictions.zip' file and submitted to CodaLab.
