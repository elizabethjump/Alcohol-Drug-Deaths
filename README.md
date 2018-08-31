# Alcohol-Drug Deaths

This project contains code and files to clean VRBIS data, merge VBRIS data with multiple cause of death files (if needed) and to get drug and alcohol numbers for CSTE metrics

All of the files are written in R markdown.  

Order of scripts:

- Run the cleaning files first. Either run: 
     - VRBIS Data Cleaning for VRBIS files with multiple cause information or 
            OR
    - MCOD cleaning and then VRBIS + MCOD Data Cleaning if you need to merge MCOD files with VRBIS
- The cleaning scripts will create datasets to use in the Alcohol and Drug scripts. 

- if you're merging VRBIS and MCOD, you might need to run to the mcod cleaning script. This code takes the MCOD data from the raw format and puts it into labelled columns
