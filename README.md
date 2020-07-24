# MSA2020
MSA Data Science Pathway

Properties.csv is the original file provided, and otagodata.xslx is the Excel file containing the NZ Deprivation Index provided by the University of Otago.

ml-create-dataset.ipynb creates a dataset from the Properties.csv and adds in the NZDep2018 and Census Population as additional columns. 
The completed dataset is output as final_dataset.csv.

ml-cleaning.ipynb checks the dataset for NaN values, and handles them depending on what column they belong to. There is also some data analysis done on the cleaned dataset, such as the datatypes, correlation matrics and pairplots on the attributes. It also converts the CV value into the log and appends it as another attribute in the dataset. 
The cleaned dataset is output as full_dataset.csv.

ml-modelling.ipynb creates a machine learning model from the full_dataset.csv, and uses it to predict the CV log value for properties. Both Random Forest and Linear Regression models were briefly explored and results are shown as scatterplots.

The final report is the AnalysisReport.pdf.
