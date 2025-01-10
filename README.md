# Fetal Health Classification

Classificar a saúde de um feto em normal, suspeita ou patológica usando dados de CTG (Cardiotocograms)

## Download de Fetal Health com Kaggle CLI

    #!/bin/bash
    kaggle datasets download andrewmvd/fetal-health-classification

## Dataset

Dados sobre a saúde do feto baseados na leitura de ardiotocograma, em inglês, Cardiotocograms (CTG). Disponível em:

    https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data

## Objetivo

Classificar a saúde de um feto em normal, suspeita ou patológica usando dados de CTG (Cardiotocograms).

#### Variáveis:


Variáveis independentes | Descrição
------------------------|------------------------------------
'baseline value'        | baseline fetal heart rate (FHR)
'accelerations'         | number of accelerations per second
'fetal_movement'        | number of fetal movements per second
'uterine_contractions'  |  number of uterine constractions per second
'light_decelerations'   | number of LDs per second
'severe_decelarations'  | number of SDs per second
'prolongued_decelerations' | number of PDs per second
'abnormal_short_term_variability' | percentage of time with abnormal short term variability
'mean_value_of_short_term_variability' | mean value of short term variability
'percentage_of_time_with_abnormal_long_term_variability' | percentage of time with abnormal long term variability
'mean_value_of_long_term_variability' | mean value of long term variability
'histogram_width'       | width of the histogram made using all values from a record
'histogram_min'         | histogram minimum value
'histogram_max'         | histogram maximum value
'histogram_number_of_peaks' | number of peaks in the exam histogram
'histogram_number_of_zeros' | number of zeroes in the exam histogram
'histogram_mode'            | hist mode
'histogram_mean'            | hist mean
'histogram_median'          | hist median
'histogram_variances'       | hist varience
'histogram_tedency'         | histogram trend

Variável dependente | Descrição
--------------------|------------------------------------
'felt_health'       | fetal health: 1 - normal; 2 - suspect; 3 - pathological  