# SQL PORTFOLIO

This portfolio showcases my SQL skills using diverse sets of datasets.

#### COMPANY LAYOFFS PROJECTS

I used SQL to query to create a database, tables and upload data to analyze company layoffs.

I presented layoffs by:
* location
*	industry
*	stage 
The companies with highest percentage of layoffs were startups.

I also cleaned the data by removing duplicate values and replacing blank cells by nulls.

I made extensive use of the following:
*	WINDOW FUNCTIONS
* TRIM
*	COMMON TABLE EXPRESSION
*	UPDATE

The data was obtained through kaggle. 

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

#### FLU SHOT DATA PREPARATION PROJECT

Using data from Synthea, I analyzed data pertaining to flu shots in a healthcare system for a dashboard that be found at the following link:

https://public.tableau.com/views/FluShotDashboard_17188300872990/FluShotAnalysis?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

I used SQL queries to prepare the data for visualization by creating a single table with all values needed for analysis.

I made extensive use of the following:
*	JOINS
*	COMMON TABLE EXPRESSION
*	INNER QUERIES


#### REFERENCES

https://www.kaggle.com/datasets/swaptr/layoffs-2022. 06, 21, 2024

Jason Walonoski, Mark Kramer, Joseph Nichols, Andre Quina, Chris Moesel, Dylan Hall, Carlton Duffett, Kudakwashe Dube, Thomas Gallagher, Scott McLachlan, Synthea: An approach, method, and software mechanism for generating synthetic patients and the synthetic electronic health care record, Journal of the American Medical Informatics Association, Volume 25, Issue 3, March 2018, Pages 230–238, https://doi.org/10.1093/jamia/ocx079

https://www.hcahpsonline.org Centers for Medicare & Medicaid Services, Baltimore, MD. 06, 19, 2024
