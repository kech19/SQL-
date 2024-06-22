# SQL PORTFOLIO

This portfolio showcases my SQL skills using diverse sets of datasets.

#### PRODUCT MANUFACTURING ANALYSIS

I used SQL to query to create a database, tables and upload data to analyze company data pertaining to product manufacturing and logistics.

I calculated:
* number of product offerings per product type
*	total sold, revenue and availability
*	order quantities by product type and gender
*	defect rates by product type
*	shipping costs by shipping carriers
*	products with highest shipping costs and defect rates by carriers and transportation mode
*	ranking the products based on price with product type

I made extensive use of the following functions:
*	JOINS
*	WINDOW FUNCTIONS
* AGGREGATE FUNCTIONS
* CTE

###### Findings
Skincare products had 2x defect than cosmetics.
Nonbinary skincare was most ordered and haircare female was the least ordered out of people with known genders.
Thorough analysis of skincare products is recommended.
Obtaining gender data on more patients will allow better customer segmenation based on gender.
Analysis of routes taken by Carrier B, weight of products could and distance to delivery could help figure out why it had the highest shipping costs.

The data was obtained from Kaggle.

#### COMPANY LAYOFFS PROJECTS

I used SQL to query to create a database, tables and upload data to analyze company layoffs.

I presented layoffs by:
* location
*	industry
*	stage

I also cleaned the data by removing duplicate values and replacing blank cells by nulls.

I made extensive use of the following:
*	WINDOW FUNCTIONS
* TRIM
*	COMMON TABLE EXPRESSION
*	UPDATE

###### Findings
The companies with highest percentage of layoffs were startups. Recommended to apply to more established companies to decrease the probability of being laid off.

The data was obtained through Kaggle. 

#### HOSPITAL ENCOUNTER PROJECT

The hospital project uses simulated patients data obtained from Synthea. 

I used SQL queries to analyze the data and returned the following:
* types of encounters
*	patients in certain type of encounters
*	number of patients with a particular condition
*	conditions with a certain number of occurrences
*	type of vaccines given to people with a particular condition
*	average payer coverage by race
*	total claim by zip code

I made extensive use of the following functions:
*	JOINS
*	INNER QUERIES
*	WINDOW FUNCTIONS
* AGGREGATE FUNCTIONS
*	SET OPERATORS

###### Findings
A lot of patients fell under the outpatient category. One of the most common reasons for visits were mental health disturbances. These patients could be linked to great local resources to prevent emergency visit to the hospital instead of going to a crisis center.

#### HCAHPS PATIENT SATISFACTION DATA CLEANING PROJECT

HCAHPS collects data about patient experience during a hospital by asking a series of questions. These questions were analyzed for hospitals over the US to gauge how they were doing comparatively to each other on certain metrics such as the 'Percent of Patients Rating Hospital 9-10', how far a hospital score was from the average in the cohort and the spread of the difference in score per questions asked on the survey.

The dashboard can be accessed through the link below:

https://public.tableau.com/views/HCAHPS_Patient_Satisfaction/HCAHPSDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

The data was obtained from the Centers for Medicare & Medicaid Services.

I used SQL queries to clean and prepare the data for visualization by creating a single table with all values needed for analysis.

I made extensive use of the following:
*	LPAD
*	to_date
*	JOINS
*	WINDOW FUNCTIONS
*	COMMON TABLE EXPRESSION

###### Findings
There was more variation in the 'Always quiet at night' question in the medium cohort in WA for example. Patients rating 9-10 ranged from 75% to low 50s. The survey response rate tend of be less than 30% and the data might fail to capture the totality of the experience during visits.

#### FLU SHOT DATA PREPARATION PROJECT

Using data from Synthea, I analyzed data pertaining to flu shots in a healthcare system for a dashboard that be found at the following link:

https://public.tableau.com/views/FluShotDashboard_17188300872990/FluShotAnalysis?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

I used SQL queries to prepare the data for visualization by creating a single table with all values needed for analysis.

I made extensive use of the following:
*	JOINS
*	COMMON TABLE EXPRESSION
*	INNER QUERIES

###### Findings
Younger than 18 and above 40s were the most vaccinated with rates above 90%. Native Americans constituted the only group with vaccination rates above 90%. As the year progressed so did the share of people vaccinated.

#### REFERENCES

https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis. 06, 21, 2024

https://www.kaggle.com/datasets/swaptr/layoffs-2022. 06, 21, 2024

Jason Walonoski, Mark Kramer, Joseph Nichols, Andre Quina, Chris Moesel, Dylan Hall, Carlton Duffett, Kudakwashe Dube, Thomas Gallagher, Scott McLachlan, Synthea: An approach, method, and software mechanism for generating synthetic patients and the synthetic electronic health care record, Journal of the American Medical Informatics Association, Volume 25, Issue 3, March 2018, Pages 230–238, https://doi.org/10.1093/jamia/ocx079

https://www.hcahpsonline.org Centers for Medicare & Medicaid Services, Baltimore, MD. 06, 19, 2024
