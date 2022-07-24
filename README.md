# Data＆Methodology

This paper makes the simple assumption that only bank fees and household income affect whether people use a bank account or not. I conducted a statistical analysis to understand the effects of annual bank charges and annual household income on bank usage. For this purpose, bank fees, household income, and bank usage data are used.

(1) Bank fees data: This paper uses the survey data by Bankrate (https://www.bankrate.com/banking/checking/checking-account-survey/) for bank fees data. Bankrate can obtain two types of bank cost data: (a) average monthly service fee and (b) average overdraft fee per instance. A monthly service fee or maintenance fee is a charge that account holders may incur monthly just for having a checking account with a financial institution. An overdraft fee is incurred when you spend more money than you have available in your bank account. You can overdraw your account by writing checks, swiping debit cards, withdrawing cash at ATMs, and setting up an automatic debit card or ACH payments. The FinHealth report (https://cfsi-innovation-files-2018.s3.amazonaws.com/wp-content/uploads/2021/04/19180204/FinHealth_Spend_Report_2021.pdf p.7) found that 43 percent of vulnerable households with checking accounts reported having overdrawn in the past year and incurred a related fee, with 9.6 overdrafts on average. For regression analysis, the annual bank fees are calculated as the sum of 12 times the monthly service fee and 9.6 times the average overdraft fee per incident. 

(2) Household income data: This paper uses U.S. census data (https://www.census.gov/data/tables/2021/demo/income-poverty/p60-273.html) for household income data. According to the FDIC data (https://www.fdic.gov/analysis/household-survey/2019appendix.pdf “A.6 Interest in Having a Bank Account, Among Unbanked Households, by Previous Bank Account Ownership and Household Characteristics, 2019”, p.9) in 2019, of the 6.9 million unbanked households, 3.2 million (about 47%) have annual household incomes below $15,000, and 5.1 million (about 75%) have annual household incomes below $30,000. Given that unbanked households are more likely to be low-income households, I use the bottom 20th percentile of household income (approximately $25,000) for the analysis from “Table A-4a.Selected Measures of Household Income Dispersion: 1967 to 2020" (https://www2.census.gov/programs-surveys/demo/tables/p60/273/tableA4.xlsx). According to a footnote in Table A4, the income data are adjusted for inflation using the Consumer Price Index data.

(3) Bank usage data: This analysis uses FDIC Survey on Household Use of Banking and Financial Services as a source for bank usage data. This survey began in 2009 and is conducted every two years. This analysis uses data from 2009 to 2019. Three types of bank usage data can be obtained: (a) the unbanked rate,  (b) the underbanked rate, and (c) the rate of unbanked households that cannot afford a bank account for financial reasons. The sources of the respective data are as follows.

(a) unbanked rate:

   2019 data: How America Banks: Household Use of Banking and Financial Services 2019 FDIC Survey Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2019appendix.pdf) A.2 Unbanked Rates by Household Characteristics, 2015–2019, p.3
   
   2017 data: 2017 FDIC National Survey of Unbanked and Underbanked Households Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2017/2017appendix.pdf) A.3 Unbanked Rates by Household Characteristics, 2013-2017, p.5
   
   2015 data: 2015 FDIC National Survey of Unbanked and Underbanked Households Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2015/2015appendix.pdf) AA.1 Banking Status by Household Characteristics, 2015, p.1
   
   2013 data: 2013 FDIC National Survey of Unbanked and Underbanked Households Appendices
            (https://www.fdic.gov/analysis/household-survey/2013/2013appendix.pdf) A-1a Banking Status By Household Characteristics, 2013, p.6
   
   2011 data: 2011 FDIC National Survey of Unbanked and Underbanked Households 2011 Appendices
            (https://www.fdic.gov/analysis/household-survey/2011/2011-unbankedreport-app-a-g.pdf) 
            Table A-1 2011 Household Banking Status by Demographic Characteristics, p.50
            
   2009 data: 2009 FDIC National Survey of Unbanked and Underbanked Households 2009 Appendices
            (https://www.fdic.gov/analysis/household-survey/2009/2009appendix.pdf) 
            Table A-1 Unbanked Households and Their Demographic Characteristics, p.48
            
 (b) underbanked rate:
 
   2019 data: GAO, Regulators Have Taken Actions to Increase Access, but Measurement of Actions’ Effectiveness Could Be Improved
             (https://www.gao.gov/assets/gao-22-104468.pdf) 
             Unbanked and Underbanked Households in the United States p.5
             (NOTE) FDIC did not report on the number of underbanked households in 2019, GAO estimated the number by recreating the underbanked group in the 
                    2019 data (using FDIC’s 2017 definition). 
   
   2017 data: 2017 FDIC National Survey of Unbanked and Underbanked Households Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2017/2017appendix.pdf) A.4 Underbanked Rates by Household Characteristics, 2013-2017, 2013-2017, p.7
   
   2015 data: 2015 FDIC National Survey of Unbanked and Underbanked Households Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2015/2015appendix.pdf) AA.1 Banking Status by Household Characteristics, 2015, p.1     
   
   2013 data: 2013 FDIC National Survey of Unbanked and Underbanked Households Appendices
            (https://www.fdic.gov/analysis/household-survey/2013/2013appendix.pdf) A-1a Banking Status By Household Characteristics, 2013, p.6
            
   2011 data: 2011 FDIC National Survey of Unbanked and Underbanked Households 2011 Appendices
            (https://www.fdic.gov/analysis/household-survey/2011/2011-unbankedreport-app-a-g.pdf) 
            Table A-1 2011 Household Banking Status by Demographic Characteristics, p.50
   
   2009 data: 2009 FDIC National Survey of Unbanked and Underbanked Households 2009 Appendices
            (https://www.fdic.gov/analysis/household-survey/2009/2009appendix.pdf) 
            Table A-12 Underbanked Households and Their Demographic Characteristics, p.58   
            
 (c) rate of unbanked households that cannot afford a bank account for financial reasons: In this analysis, households that answered "Bank Account Fees Are Too High," "Bank Account Fees Are Too Unpredictable," or "Don't Have Enough Money" are counted as households that cannot afford a bank account for financial reasons.
   
   2019 data: How America Banks: Household Use of Banking and Financial Services 2019 FDIC Survey Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2019appendix.pdf) 
            A.8 Main Reason for Not Having a Bank Account, Among Unbanked Households, by Previous Bank Account Ownership, 2019, p.13
   
   2017 data: 2017 FDIC National Survey of Unbanked and Underbanked Households Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2017/2017appendix.pdf) A.17 Main Reason Households Were Unbanked by Previous Banking Status, 
             2017 , 2013-2017, p.30
   
   2015 data: 2015 FDIC National Survey of Unbanked and Underbanked Households Appendix Tables
            (https://www.fdic.gov/analysis/household-survey/2015/2015appendix.pdf) A.17 Main Reason Households Were Unbanked by Previous Banking Status, 2015, p.34        
   2013 data: 2013 FDIC National Survey of Unbanked and Underbanked Households Appendices
            (https://www.fdic.gov/analysis/household-survey/2013/2013appendix.pdf) A-9 Main Reason Households Were Unbanked By Previous Banking Status, 2013, p.25        
   2011 data: 2011 FDIC National Survey of Unbanked and Underbanked Households 2011 Appendices A - G - PDF
            (https://www.fdic.gov/analysis/household-survey/2011/2011-unbankedreport-app-a-g.pdf) 
            Table A-20 2011 Reasons Households are Unbanked by Previous Banking Status, p.69        
          
# Visualization

Charts 1 through 4 were created using Tableau. Please refer to the tableau file in the repository for detailed instructions.

# Statistical analysis
