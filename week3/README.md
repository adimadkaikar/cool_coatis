# Week2 CMEE Groupwork

## Description:

This directory contains the week2 CMEE Groupwork from Group 3. The results generated will be saved to the results directory.

## Languages:

Python, R, shell, LaTeX

## Structure:

*PP_regress_loc.R* - The linear regression relationship between the predator mass and prey mass is examined, and the analysis is separate by the dataset's *Location* field.

*TAutoCorr.R* - The source script to answer the question: "Are temperatures of one year significantly correlated with the next year (successive years), across years in a given location?"

*FloridaYears.tex* - The interpretation of the results generated by the script *TAutoCorr.R*.

*get_TreeHeight.R* - This script takes the input from the command line and saves the output in the results directory. The dataset *trees.csv* is used as an example.

*get_TreeHeight.py* - This is the Python version of the above script.

*run_get_TreeHeight.sh* - The shell script runs the above two scripts with the default input, which is the *trees.csv* in the data directory.

##### Dependencies:

*sys* - used for taking the input parameter from command line

*os* - used to split the string of input and eliminate the extension in R

*pandas* - for csv reading in Python

*numpy* - for mathematical operation when defining the tree height

*tools* - used to split the string of input and eliminate the extension in Python

*tidyverse* - for selecting data and subsetting

## Authors and contact:

+ Aditi Madkaikar; arm122@ic.ac.uk
+ Agnes Szwarczynska; aas122@ic.ac.uk
+ Ruth Brown; ruth.brown2222@imperial.ac.uk
+ Xuan Wang; xuan.wang22@imperial.ac.uk
+ Shengge Tong, shengge.tong22@imperial.ac.uk