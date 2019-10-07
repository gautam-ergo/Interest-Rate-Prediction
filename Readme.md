The goal of this project is to build a machine learning model that can predict the most appropriate interest rate for a given set of parameters provided by the Lending Club transactional loan data.


The file is a matrix of about 890 thousand observations and 75 variables. These files contain complete loan data for all loans issued through the 2007-2015, including the current loan status (Current, Late, Fully Paid, etc.) and latest payment information.
Kaggle provides a ‘loan.csv’ file and a dictionary for the various columns being used in the input file, it is in the form of .xlsx.


Step1: Loan .csv file should be used as the input file and the code would produce cleaned.csv after manual pre-processing

Step 2: Cleaned.csv should be used as input for Pre-Processing notebook. 

Step 3: Pre-Processing notebook will produce two CSV file namely, Features_data.csv and Features_Data_final.csv

Step 4: Features_Data_final.csv should be used as the input file for executing Neural Net notebook 

Step 5: Features_Data_final.csv should be used as the input file for executing Random Forest notebook

Step 6: pip install ‘tpot’ module before executing TPOT notebook.

Step 7: Cleaned.csv should be used as the input for TPOT notebook.


Neural Net, Random Forest and TPOT are the models that were implemented as part of prediction model creation. Achieved an accuracy of around 91% for Neural Net and 92% for Random Forest. 
