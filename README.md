# Future_Intern_Task1
Perform Data Cleaning- Clean a dataset by removing missing values and outliers
a) To identify and treat missing values(using filters in excel)
   -> identify missing values
        * Count total number of values in each column
        * if no. of record > no. of values then missing values
b) Treatmnet
   -> Deletion of row:
       * if missing values are 50% or more than we'll discard those rows.
       * for rest data we'll calculate mean, median, mode using available value & replace.
c) Outliers
  * data points that are significantly different from other data points are called outliers.
  * Outliers can skew the interpretation of data.
  * They can be accurate or innacurate.
  -> Outiliers identification
    * using visualization(charts like histogram and scatter helps to identify outliers)
    * statistical way 1) sort data
                      2) Calculate Quartile(=quartile(array containing values, 1/2/3 for Q1/Q2/Q3 respectively)
                      3) Inner and outer fences
                      4) Lower Bound = Q1-(1.5*(Q3-Q1))
                      5) Upper BOund = Q3+(1.5*(Q3-Q1))
  d) outlier Treatment
     * delete outlier data
     * Revisit data points
      
       
