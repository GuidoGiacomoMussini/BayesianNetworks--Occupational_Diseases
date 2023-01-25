# AMS-Bayesian_Network-Occupational_Diseases

Bayesian network used to analyse a dataset (from the INAIL website) containing information on occupational diseases reported in Italy between July and December 2022. 

The 'PreProcessing' R file takes as input all the .csv files contained in the zip folder, with the exception of 'ImpData', which is output from 'Preprocessing' itself. 

The other two files only take 'ImpData' as input.
'ShiniyApp' file creates a reactive dashboard from which you can make simple conditional probability queries
