# BUSINESS UNDERSTANDING
The purpose of this project was to understand custormer transaction patterns,payment methods gender distribution regional performance and monthly deposit trends
Understanding customer payment behaviours is important for identifying trancsaction patterns and making informed  business decisions.This project examine Mobile money for detection of early sign of financial harship 
to understand how custormer make payment across different months genders, and regions.The analysis focus on deposit,paybill,bank transfers,and monthly payment activities.
## Project objective
1. To compare deposits made by different genders from Months 1(M1)to Month 6(M).
2.  To examine the relationship between gender and bank tranfer
3.  To analyse paybill transactions across diffrerent regions
4.  To identify monthly changes in custormers
5.  To present findings using charts and tables
6.  To identify patterns that can support better business decisions.
## Business questions
- Which gender record highest?
-How do deposit change from M1 to M6?
-Which gender has more bank transfers?
-Are they difference in in payment behaviour across the region?
-Which payment method is commonly used?
# DATA UNDERSTANDING
- Thedata was obtained from https://zindi.world/competitions/financial-stress-prediction-challenge
- The dataset was obtained and imported into microsoft Excel for analysis
## Description of dataset
It contain the information used to examine custormer transaction and payment behaviour

Variable           Description
- Gender           Gender category of the custormer
- Deposit          Amount deposit by custormer
- Bank transfer    payment made through bank transfer
- Paybill         Payment made through paybill
- Region          Geographical area of custormer
- MI              M 1 transaction information
- M2              M 2 transaction information
- M3              M 3 transaction information
- M4              M 4 transaction inforamtion
- M5              M 5 transaction information
-M6               M 6 transaction information
# DATA PREPARATION
Data preparation involves cleaning,organising,and formating the dataset to make suitable for analsis
Microsoft Excel were used to prepare Mobile Money for eary detection for financial hardship       
## Datacleaning
## check misising values
- blank cells were identify using filters
- Numeric blanks transaction field were treated as zero only where blanks represent no record transaction ;otherwise ,they left blank and excluded from averages.
## Remove Duplicates
 - Duplicate recors were identify using Excel Data> Remove duplicate feature.
 - The duplicate_removal cirteria were based on the field that uniquely identify a custormer transactions where a unique customer or transactions ID was available it was used as primary creterion
   ## Correcting Column Names
  - Ensure thta column heading were clear and understandable
  - Heading were starndardise by removing unnecessary spaces,correcting spellingsand using consistent names such as Gender,Region,Deposit,Bank transfer,Paybill,M1,M2,M3,M4,M5,M6.
    ## Formating Data
    -Applied appropriate formating to make the dataset easier to read and analyse.
    -The data was converted into Excel table
    -Filters enable headers
    ## Organising Monthly Data
    Arrange monthly informations from M1 to M6 for easier comparison
    # MODELING
    Involves applying analytical technique to discover pattern and relationship in the dataset.Microsoft excel were used  to perform the analysis through formulas,pivot tables,and charts.
    ## Analysis Performed
    ## Gender Versus Bank transfer(M1-M6)
    -This analysis compare Bank transfer made by different gender by six months.
    -The pivot table were used Gender in the Row area and the Bank transfer in values area with the field value summarised using sum.
    - It was display in bar chart
      <img width="630" height="433" alt="image" src="https://github.com/user-attachments/assets/652515e1-8c75-46ad-b41a-2f837cfe9f7a" />

  

    ## Region Versus Paybill
-This analysis compare Paybill transaction across different regions.
-The pivot used region in the Row area and Paybill in the values.
-The sum were used to summarise.
-The  region were sorted from highest to lowest total
-It was display in chart
<img width="622" height="438" alt="image" src="https://github.com/user-attachments/assets/f829d75e-ea41-403a-acb9-d3bdde8cad72" />


  ## Age group Versus Deposit
-This analysis compare Deposit transaction across different Age group over six months.
-The pivot were used  Age group in the Row area and the Deposits in values area with the field vallue summarised using sum.
- Display in charts
  
<img width="627" height="487" alt="image" src="https://github.com/user-attachments/assets/79b2daa1-2bf1-4760-b5cc-113cdd8d6057" />

 # EVALUATION 
  Evaluation involves reviewing the results obtained from the analysis to determine whether the project objectives and business questions have been adress
  The charts and Pivot tables were examine to identify pattern in deposit,bank transfer,and paybill transactions
  ## Key area of Evaluation
 
 ## Monthly Deposit Analysis
 - Compare the deposit between gender from M1 to M6 identify the monthly changes and difference
## Bank Transfer Analysis
  -Examine bank transfer values to understand payment differences genders
  ## Regional Paybill Analysis
 - Compare Paybill transaction across regions to identify difference in regional payment activity
 - Identify which Regin with the highest Paybill value
 - Identify the Region with the  lowest paybil transaction
 - 
## Gender Distribution
  -Reviewd the gender distribution to understand the comparison of the customers.
  - Whether the distribution was balance or uneven
  - The Number of customer in each gender category
  ## liduidty
  -Identify monthly changes in cash flow
  -Compare deposit with widthrawals,if withdrawal are available
  
  ## Findings
  - Gender with the highest bank transfer was 166037091.2
  - The Region with the Highest paybill transaction was 30291188.74
 
    # DEPLOYMENT
    Deployment involves presenting and sharing the results of the analysis so that other people can understand the findings.The project documentation,dataset,and visualisations are organised in a Github repository.The Project was analyse using Microsot excel.After complection  data cleaning ,preparation,Modelling,and Evaluation.The main purpose is to make Project findings understandable,accessible, and useful to other peolple who may want to review the analysis.Git and Gihub used to manage Project files,track changes and store the project documentation.
## project tool
    -Zindi  The data source was obtain
    - Microsoft Excel  Cleaning and analyzing data
    - Git - track changes
    - Github  store and share project
    
 ## Contributor
      Brenda Kimuge
      
   




 
  
  


 
    
    
    




