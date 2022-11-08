# TEM_Analysis

These programs create a sample model of response function of NCE (net carbon exchange) to forest stand age, and annual global average temperature and CO2 levels based on outout from the Terrestrial Ecosystem Model (version TEM-Hydro)

Files should be run in this order if using output from TEM

 1. process_TEM_cohort_output.ipynb - processes TEM input and output data for analysis
 2. create_dataset_for_sample_model.ipynb - creates a dataset for the model based on processed output from (1)
 3. sample_output_generalized_additive_model.ipynb - uses dataset from (2) to create a generalized additive model that predicts NCE
 
