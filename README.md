Linear Regression on Vehicle Fuel Economy Data
----------------

This project involves using SAS Enterprise Miner to analyze a dataset containing vehicle fuel economy information.  I will create several distinct linear regression models to predict the value of a vehicle's fuel economy.  Each model will use different parameters and variable selection methods.  I will then evaluate these models to determine which is the most accurate.

The full report can be found in the file "Linear Regression.pdf".  This report shows a complete breakdown of my analysis, including problem identification, motivation, data exploration, data preparation, data sampling and partitioning, predictive model development, model results and tuning, model comparison, and proposed solutions.  Tables and visualizations are included in the appendix.

The dataset "cars2010.csv" was created by Kuhn and Johnson (2014).  It is located within the "AppliedPredictiveModeling" R package, which can be obtained below:

https://cran.r-project.org/web/packages/AppliedPredictiveModeling/index.html

To access the original data files, download the R release version of “AppliedPredictiveModeling_1.1-6.zip” for your operating system (I use Windows).  Extract the zip file, navigate to the data folder, and locate the file “FuelEconomy.RData”.  This file contains three separate tables for 2010, 2011, and 2012 data.  The 2010 data table includes the highest number of records, thus it is the one I used in this project.  Since this file is in R workspace format, you need to convert the 2010 data table into a .csv file.  I did so in RStudio by using the “write.csv” R command.  Next, the file needs to be converted from .csv to .sas7bdat, which can be done within SAS Enterprise Miner.  Finally, the data source needs to be imported into your SAS EM project.

The process flow diagram I created for this project (seen in Figure 1 of my report's appendix) is included in the file "linear regression diagram.xml".  The requirements are described in the file "requirements.txt".  To use this diagram, you need to import the .xml diagram into your SAS EM project.


References:

Kuhn, M., & Johnson, K. (2014, July 25). AppliedPredictiveModeling: Functions and Data Sets for 'Applied Predictive Modeling'. Retrieved October 6, 2017, from https://cran.r- project.org/web/packages/AppliedPredictiveModeling/index.html