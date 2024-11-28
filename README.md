# Master_Thesis_Final
Repository for the master thesis


This repository contains the data and Python code used for my master’s thesis at the Hertie School for the Master of Science of Data Science for Public Policy. 

My research topic, which holds significant implications for the academic community, potential collaborators, and policymakers, is:  From Fields to Borders: The Impact of Climate Scenarios on Migration Patterns from Central America and Mexico to the US.

This thesis examines projected migration patterns from Guatemala, Honduras, Mexico, and El Salvador under four climate scenarios (SSP119, SSP245, SSP370, SSP585) from 2023 to 2100. It analyzes the influence of varied emission levels and socioeconomic factors on migration, revealing significant deviations from historical trends guided by statistical evidence and climate data projection. 

Data used for the analysis: 
1.	Historical data from TRAC on undocumented immigrants for the San Diego, Tucson, and Rio Grande border crossings. Data retrieved from:
a.	 https://tracfed.syr.edu/trachelp/tracsite/helptrac_atwork.shtml
2.	Projected data from Deutsches Klimarechenzentrum (DKRZ). (n.d.). The SSP Scenarios. Data retrieved from: 
a.	https://www.dkrz.de/en/communication/climate-simulations/cmip6-en/the-ssp-scenarios
3.	Historical data for additional variables used in the model was retrieved from the World Bank.

Some of the results:
![image](https://github.com/user-attachments/assets/012f1a6f-acc6-4bfa-9dff-9729a6cafbf6)


![image](https://github.com/user-attachments/assets/400deb3f-66b7-49ba-9c52-72986757b918)



There are three scripts for each border crossing for each of the four countries, giving 12 scripts. Each script generates projections under each of the four climate scenarios, generating graphs projecting the increase in immigration and an OLS Regression Results .txt file specific to each country under a specific scenario on each border crossing.
-	Input CSV files for the models are located in the folder file: INPUTS_OUTPUTS_NEW_VARIABLES_ML
-	All_outputs folder file contains the output files from all the scripts.
A crawler script was also created (Final_Graphs.ipynb) to go into the All_outputs folder and create final graphs taking the output CSV for every script to create a summary of projections per country under each scenario. 
-	The route to the graphs: Script_Output_Graphs_Dataframes/Crawler_Output_Graphs

For further questions, please reach out by sending an email to: fernancors@hotmail.com
