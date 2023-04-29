# STAT0023-Generalised-Linear-Models

README: Predicting Proportion of 'Leave' Votes in UK Electoral Wards

Introduction:
This repository contains code to build a statistical model for predicting the proportion of 'Leave' votes in UK electoral wards based on various social, economic, and demographic characteristics. The data for the analysis was obtained from the 2016 EU referendum and the 2011 UK census.

Background:
On 23rd June 2016, the UK held a referendum to decide whether to remain part of the EU or not. The result was unexpected, and there was extensive commentary on the reasons for it at the time. Martin Rosenbaum, a Freedom of Information specialist at the BBC, calculated some statistical associations between the proportion of 'Leave' votes in a ward and some of its social, economic, and demographic characteristics. However, he did not investigate them jointly, which could be important in understanding the reasons behind the voting outcome.

Tasks:

1. Read the data into R and carry out necessary recoding.
2. Carry out an exploratory analysis to reduce the number of candidate variables and identify important features of the data.
3. Develop a statistical model using a range of models and diagnostics to assess them. Recommend a single model suitable for interpretation, which should be either a linear model, a generalized linear model, or a generalized additive model.
4. Use the chosen model to predict the proportion of 'Leave' votes for each of the 267 wards with missing voting data and estimate the standard deviation of the predictions.
Data:
The data is provided in a CSV file, ReferendumResults.csv, in the 'In-course assessment 2' section of the STAT0023 Moodle page. The file provides values of around 45 variables that may be relevant in understanding the voting outcome for each of the 1070 electoral wards. The numbers of 'Leave' votes are provided for the first 803 wards but not for the final 267 wards, which are given as -1 in the data file.

Getting Started:
To replicate the analysis, download the data file and the R code from this repository. Follow the instructions provided in the code to read the data into your chosen software package, carry out exploratory analysis, develop a statistical model, and predict the proportion of 'Leave' votes for the 267 wards with missing data.

Contributing:
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments:
The data used in this analysis was obtained from the 2016 EU referendum and the 2011 UK census. Thanks to Martin Rosenbaum for his article "Local voting figures shed new light on EU referendum" and for sharing his census data.
