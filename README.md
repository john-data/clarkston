# Clarkston Consulting Dataset Processing

This notebook:
1. reads the `CustomerExtract.csv` and `CustomerSpec.xlsx` files, 
2. profiles the data,
3. performs data quality checks
4. cleans up data quality issues (for example, removing special characters in the **Name 1** field) 
5. applies any required transformations defined in the spec
5. and outputs cleaned data is exported as a flat file named `CustomerLoad.csv`.

### PLEASE NOTE:
This notebook is created for re-usability based on the Customer Spec excel sheet. Please follow the below steps to produce the appropriate output.

## Installation
1. Insure you have python installed and use a virtual envrionment (`venv` or `conda`)
2. `pip install -r requirements.txt`
3. Press Play!