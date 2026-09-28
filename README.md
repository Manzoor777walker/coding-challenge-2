# coding-challenge-2
# Insight found in data set and fixing inconsistent data 
     1)A sales dataset is prepared manually by multiple teams and shows the following problems:
            ● Inconsistent product names due to spacing, casing, and spelling differences
            ● Multiple columns contain merged text values (e.g., Region_Product_Code)
            ● Duplicate records exist, but removing them incorrectly affects totals
            ● Some numeric fields contain text and extra symbols
            ● The final report requires filtered summary statistics (mean and standard deviation)
                  for only valid records
                        1)using power query tool in excel 
                        2)Each column in the dataset has been assigned according to its specific data types.
                        3)Fixing the inconsistent data by using Trim,clean function
                        4)Assign the text data starting with capitalize by using "capitalize each toggle case " option.
                        5)Error values change into null ,miss spelling typos,symbols etc... by using replace value method.
                        6)Remove duplicate by using remove duplicate function.
                        7)After Data cleaning load the data to excel worksheet and create custom sales amount column with missing values for mentioning mean and standard deviation.
                      by using this formula to find the mean of the mentioned above the data set {=IF(ISBLANK(E2),AVERAGE($E$2:$E$41),E2)} and  {=STDEV.S(FILTER(E2:E41,J2:J41="Valid"))}

# prevent future data issues and ensure the results remain accuratewhen new data is added.
                                      To prevent future data issues and maintain accuracy as new data is added, I implemented automated data validation rules to filter out invalid records and duplicate entries prior to analysis.
                                            
        

         
