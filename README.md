# AIDdecisions
Please keep the structure of the files when downloading to avoid any confusion among the files for the Bayesian analyses and the strategy difference files. You will need to change all file paths in the R files to correspond with your path to the files.

Bayesian Modeling: This folder contains everything you need to run the Bayesian analyses in the manuscript/paper. You will need to how R and JAGS loaded on your computer to run the analyses. Both are freely available online: 
https://www.rstudio.com/products/rstudio/
https://sourceforge.net/projects/mcmc-jags/files/

Code
run_2cp: This file will output the change point for each individual at each cost level in long format. These analyses take a long time (>1 week) as they are computationally intensive.
Fn_2cp: This is the function being called in the run_2cp R file. You should not need to change anything in this file.
Beta_driveaware: This file computes the Bayes factors for each decision making classification. This will output those Bayes factors as well as the theta and tau values for each individual across all task conditions. 

Data
Ascending: These are the decisions each person made on the decision task across all task conditions and on the ascending limb. 
Descending: These are the decisions each person made on the decision task across all task conditions and on the descending limb.

Results
Bayes Factors: output of Bayes factor analyses for each individual on each limb.
Ascending_changepoint: change points for each individual at each level of the task on the ascending limb.
Descending_changepoint: change points for each individual at each level of the task on the descending limb.
Tau_ascending: tau values for each individual at every cost condition level on the ascending limb 
Tau_descending: tau values for each individual at every cost condition level on the descending limb
Theta_ascending: theta values for each individual at every cost condition level on the ascending limb
Theta_descending: theta values for each individual at every cost condition level on the descending limb

Strategy Differences Data: This folder contains everything you need to run the analyses on individual differences in strategy use. You will need R to run these analyses.
Longddgambles: data for each participant in wide format. Used in analyses for baseline measures of AID attitudes.
Long_data: repeated measures data for each participant in the long format. Used in mixed effects models. File contains BrAC measurements, subjective intoxication, and perceived AID dangerousness at all study timepoints. 
Bacplot: data for each participant on the highest BrAC they indicated being willing to drive in wide format. Used in analyses of AID intentions.

Code
AID attitudes and intentions: This is an R Markdown file with all of the analyses on individual differences in strategy use presented in the paper/manuscript. Please change the path files to correspond with your computing device.

Results
AID attitudes and intentions: This is a knitted HTML file from the above R Markdown file with all of the analyses on individual differences in strategy use presented in the paper/manuscript. This will recreate all tables and figures in the manuscript/paper.

Please reach out if you have any questions about the data, code, and/or results.
