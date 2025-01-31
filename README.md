# Happiness in US Analysis of the Effects of Demographic Factors during 1972 to 2021

This repository can be found at https://github.com/JunweiZhang130/Happiness-in-US-Analysis-of-the-Effects-of-Demographic-Factors-during-1972-to-2021.git    

This repository presents an exploration of the relationship between demographic factors and happiness levels in US. And the data is obtained from the *US General Social Survey*.    

## Notes for Reproduction
Since we don't have the permission to share the GSS data, you can download the raw data from its original website: https://gss.norc.org/get-the-data/stata. And the data file we used is called *GSS 1972-2021 Cross-Sectional Cumulative Data (Release 3b, February 2023)* under the *Cumulative Data Set (cross-sectional samples from all years)*. Please save the raw data you downloaded in the inputs/data. Then, run the *00preparation.R* in scripts file, this creates the datasets (*raw_data.csv* in the outputs/data).           
                                     
The paper and the graphs are based on our cleaned data, so if you prefer not to review the raw data, that's not a problem.                  

Then run the *references.bib* file (*outputs/paper*) for references and citations, after that run the *Happiness in the U.S: A Comprehensive Analysis of the Effects of Demographic Factors.qmd* file (outputs/paper).                     


The repository is organised as follows:                  
## Inputs                
we removed the raw data since we don't have the permission. If you choose to download the raw data from GSS, please store it in here (inputs/data)                

## Outputs                   
The outputs folder coontains data file, paper file and survey file.                 
##### Data File                     
Since we don't have the permission of sharing GSS data, we included our precleaning data as the raw_data.csv. This file includes all data we used in this paper. And the other files are the cleaned data for figures based on different demographic factors.                           

##### Paper File              
The .bib file contains the citations for the raw data, packages and literature used in the report.
The rmd file contains the analysis report, as well as the code used to create the report. This code was mainly used to create tables and graphs.               
The pdf file contains the same analysis report but in pdf form, and without the code. 

##### Survey File  
This file contains the QR code to access our survey and screenshots of our survey.

## Scripts            
The Script folder contains data cleaning process for each graph, simulation for each graph and a test for all cleaned data.             
 
