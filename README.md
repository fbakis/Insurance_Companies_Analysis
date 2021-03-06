# Insurance_Companies_Analysis

Data Source: https://www.tsb.org.tr/resmi-istatistikler.aspx?pageID=909


Project Aim:  The project aim is to gain knowledge on trends of total gross written premium and market share of insurance companies in Turkey.  Specifically, to compare trends of Allianz Turkey with those of other big insurance companies from 2014 to present.  Develop analytical models to predict these trends for upcoming years.


Data Pre-processing: The data is collected from the Turkish Insurers Union website - "https://www.tsb.org.tr/resmi-istatistikler.aspx?pageID=909".  The data consists of a separate Excel file for each month from 2014 to 2018.  It contains monthly gross written premium and market share figures for every insurance company, as well as company name and company code. Market share and gross written premium are numeric data fields, are always greater than zero and do not have missing values in any record.
For each spesific month-year, the Excel file is imported into Pandas library, and all data is consolidated into one Pandas dataframe, so that it can be analyzed easily.


Additional information such as seasonality can be derived from the existing data, and additional external data such as inflation rate, economic growth rate, etc. can be utilized.


At the End of Project:  We can have information about the trends of gross written premium & market share for all Turkish insurance companies since 2014. The following questions are to be answered: How did Allianz’s total gross written premium / market share change? How do trends compare across major insurance companies? What is the share of the insurance sector in the economic growth in Turkey for each year / month? How did the insurance companies share this growth? What is Allianz’s share in the insurance sector growth? By analyzing market share trends across companies, can we have an idea on customer transfers across companies? We also expect to be able to develop predictive models for gross written premium and market share trends for upcoming years. 
