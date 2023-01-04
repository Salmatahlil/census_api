# Census API - 2019 Annual Business Survey

# Introduction:

**Census Data:**
	The Census Bureau Annual Business Survey conveys information on economic and demographic characteristics for businesses and their owners by sex, ethnicity, race, and veteran status  in the United States. The survey also provides information on company summary and module business characteristics. The Annual Business Survey data was collected from online based surveys and data from Economic Census as well as administrative records. A random sample of businesses were selected and sent letters which gave instructions on how to report online. 

**Company Summary:** 
	Company Summary is also a dataset provided by the Annual Business Survey (ABS). This dataset contains information concerning general information about businesses. It contains information about sales, payroll, number of employees, and years in business. Similar to the other datasets, Company Summary also contains categorical data about business owners such as their race, sex, ethnicity, and veteran status. While there are many years to analyze, we are only concerning ourselves with the data from the years 2019 and 2020. 

**Characteristics of Businesses:**
	Characteristics of Businesses is another dataset provided by the Annual Business Survey (ABS). This dataset provides data for the respondent employer firms by categories such as sector, sex, ethnicity, race, veteran status, years in business etc for the United States. Some of the years go further in depth providing specific states and metro areas such as 2018 and 2021. The year being analyzed for this dataset is 2020 which includes survey responses from the previous year.
Characteristics of Business Owners:
Characteristics of Business Owners dataset gathers information specifically pertaining to the business owners, such as level of education completed, reasons for the acquisition of the business and how the business was acquired. The dataset for 2017 was analyzed because there were more questions on that specific survey compared to the following three years. It is worth noting that the data provided is an aggregated set of data, which limits our ability to correlate two variables. However, we are still able to make observations about our business owners as a whole.

**Module of Business Characteristics:**
	The Module of Business Characteristics (MBC) is a dataset provided by the Annual Business Survey (ABS) which is accessible via an API provided by the US Census Bureau. The data set, conducted in 2021, covers a wide range of survey topics on the business’ use of technology and the financial effects of the COVID-19 pandemic. 

# Initial Questions:
- How have industries changed as automation has increased?
- What industries have a higher number of black owners? Are they different or similar to female black owners? Are there drastic differences between the two? How -
different are they from white owners? (all in the year 2020)
- What educational background do they have? What motivates the business owners in America to run their own business? 

# Data Dictionary:
- Name
	Gives the geographic name of the region that the data is coming from.
- NAICS2017_LABEL
	The name of the industry that’s associated with the NAICS code. 
SEX_LABEL
The sex of the owner(s) of the business.
ETH_GROUP_LABEL
The ethnicity of the owner(s) of the business.
RACE_GROUP_LABEL
The race of the owner(s) of the business.
VET_GROUP_LABEL
The veteran status of the owner(s) of the business.
EMPSZFI_LABEL
The size of the company based on how many employees it has. The size is given by a range (i.e 1-4 employees).
YEAR
The year of the data 
FIRMPDEMP
Number of employer firms 
RCPPDEMP
Sales, value of shipments, or revenue of employer firms ($1,000)
YIBSZFI
Years in business code. See API2020-company-summary.pdf (census.gov) for more detailed information about the codes. 
PAYANN
Annual Payroll ($1,000)
EMP
Number of employees as a raw number 
RCPSZFI_LABEL
Sales, value of shipments, or revenue of employer firms code. See API2020-company-summary.pdf (census.gov) for more detailed information about the codes. 

# Brief Description of our Folders:

**ETL Report:**
	The ETL Report contains the cleaning and transforming steps needed to turn the census datasets into usable data frames. 

**Visualizations:**
	In this folder, you will find the code and visualizations related to our questions surrounding the datasets. There are 12 total visualizations using the seaborn and matplotlib modules. 

**Project Report:**
	In this folder, you will find the complete project report. Here you can find our analysis on the data and explaining our visualizations. This also includes our findings and results from the datasets.

**Project Presentation:** 
	The Project Presentation is a PDF file that contains the 12 visualizations from the Project Report PDF. The Report has all the initial information such as our sources, questions, and our analyzes that our visualizations refer to. 



