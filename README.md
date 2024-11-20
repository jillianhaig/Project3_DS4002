# Project3_DS4002

## Content ##
This repository contains all the necessary files and information to analyze vehicle image data. It contains a Data, Output, and Scripts folder where the user can find all of the csv files used to obtain the data, as well as scripts used for transforming and analyzing the final dataset. The repository also contains the README (this file) and the LICENSE markdown files, as well as the final presentation slides for the project. 

## Section 1: Software and platforms used 
The Python programming language was used for all analysis and coding for this project. The packages used in this project that need to be installed include: drive, files, zipfile, os, pandas, seaborn, matplotlib.pyplot, tensorflow, layers, models, ResNet50, ImageDataGenerator, train_test_split, EarlyStopping, StratifiedKFold, f1_score, accuracy_score, and numpy. Both Mac and Windows platforms were used in this project.

## Section 2: Map of documentation 
The Project2_DS4002 repository contains the following folders and files:
1. DATA folder: contains the Final Dataset subfolder, where the merged and cleaned dataset (vehicle_images_dataset.csv) can be found. It also contains the Individual Datasets folder, where one can find data for each individual csv file utilized in the study, which were cleaned and merged together to create the final dataset. Finally, the folder contains the Data Appendix pdf document, named DataAppendix.pdf.
2. OUTPUT folder: Contains png files of output from exploratory data analysis (EDA), and data visualizations. This includes any scatterplots, line graphs, relevant code output, and other visualizations the group has created for analysis.
3. SCRIPTS folder: contains three ipynb files which were created by the group to investigate the research question using statistical analysis. The scripts involve data cleaning and creation, EDA, and data analysis.
4. Final project presenation slides (DS 4002 Group 15 Project 3.pdf)
5. LICENSE markdown file
6. README markdown file

## Section 3: Instructions for reproducing results 
To replicate the methods and results of this study, one can find all the necessary tools and files from this GitHub repository. After accessing the repository, the user can download all the data from the DATA folder. The 1_DatasetCreationandCleaningProj3.ipynb file must be run first in a coding environment such as Google Colab. This file unzips the vehicle data, and it also builds the final, cohesive dataset. Next, the 2_EDAProject3.ipynb file can be run to obtain the same results from EDA that the group did. Although not imperative to the analysis for this study, the EDA portion serves as additional context into the research question and dives deeper into the variables used in the dataset. Finally, the 3_Project3Analysis.ipynb file must be run to obtain results using statistical analysis, including training and testing the model and obtaining model performance metrics such as accuracy.
