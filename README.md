# Prescribing-information(PI) scrapper
What is it?
This is a drug information scrapper that provides the details regarding the inputted drugs from the FDA website. FDA provides the exhaustive details of drugs such as their Brand names, Description, Adverse events, Dosage, etc. The details of the different drugs can be accessed from here. This tool utilizes a free API provided by openFDA website to retrieve the information for the drugs passed through it.

When to use it?
The code can be used as an internal asset to support any work (client/internal) that requires information related to drugs present on FDA website. The tool provides product details such as generic name, brand name, manufacture name, clinical studies, dosage forms, indications, mechanism of action, route of action, adverse reactions, ndc number, etc.

How to use it?
Using the code would require the following:
1.	Jupyter notebook via Anaconda installed on your laptop
2.	An API can be used to obtain details for a large number of drugs. For a small list of drugs, the API is not required. However, the API is free of charge - With an API key, we can give: 240 requests per minute, per key (120000 requests per day, per key).
3.	General knowledge of Python to update the API key, load the input and change the file paths or make any adjustments as required by the project
4.	An input csv file with the drug name column. The sample files for input and output are shown below. Input file is to be used in the format as that of the below file.
 
Step 1: User Inputs:
  A.	File path for loading Input file and the file path to store Output file.
  B.	API Key generated from the site (link). If API is not available leave it API as ‘’.
 
Step 2: Click on command “Run all”
