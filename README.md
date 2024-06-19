# SQL PORTFOLIO

This portfolio showcases my SQL skills using diverse sets of datasets ranging from healthcare and business.

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
*	JOIN
*	INNER QUERIES
*	WINDOW FUNCTIONS
* AGGREGATE FUNCTIONS
*	SET OPERATORS

#### HCAHPS PATIENT SATISFACTION DATA CLEANING PROJECT

HCAHPS collects data about patient experience during a hospital by asking a series of questions. These questions were analyzed for hospitals over the US to gauge how they were doing comparatively to each other on certain metrics such as the 'Percent of Patients Rating Hospital 9-10', how far a hospital score was from the average in the cohort and the spread of the difference in score per questions asked on the survey.

The dashboard can be accessed through the link below:

https://public.tableau.com/views/HCAHPS_Patient_Satisfaction/HCAHPSDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

The data was obtained from the Centers for Medicare & Medicaid Services.

I used SQL queries to clean and prepare the data for visualizatio by creating a single table with all values needed for analysis.

I made extensive use of the following functions:
*	LPAD
*	to_date
*	JOIN
*	WINDOW FUNCTIONS
*	COMMON TABLE EXPRESSION



#### REFERENCES
Jason Walonoski, Mark Kramer, Joseph Nichols, Andre Quina, Chris Moesel, Dylan Hall, Carlton Duffett, Kudakwashe Dube, Thomas Gallagher, Scott McLachlan, Synthea: An approach, method, and software mechanism for generating synthetic patients and the synthetic electronic health care record, Journal of the American Medical Informatics Association, Volume 25, Issue 3, March 2018, Pages 230–238, https://doi.org/10.1093/jamia/ocx079

https://www.hcahpsonline.org Centers for Medicare & Medicaid Services, Baltimore, MD. 06, 19, 2024
