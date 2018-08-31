# Alcohol-Drug Deaths

This project contains code and files to clean VRBIS data, merge VBRIS data with multiple cause of death files (if needed) and to get drug and alcohol numbers for CSTE metrics

All of the files are written in R markdown.  

Run either of the cleaning files first (VRBIS Data Cleaning or VRBIS + MCOD Data Cleaning). Those scripts will create datasets to use in the Alcohol and Drug scripts. 

- if you're merging VRBIS and MCOD, you might need to run to the mcod cleaning script. This code takes the MCOD data from the raw format and puts it into labelled columns
