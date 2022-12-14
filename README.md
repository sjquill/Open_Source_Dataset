# Open_Source_Dataset
An open source dataset of DRD4 status and patient characteristics

Documentation for ‘Opensource_data’ dataset:

Gender
-	Sex of customer. “M” denotes male, “F” denotes female. 

birthyear_group
-	A binary variable. If the year the customer was born in is less than or equal to 1980 they are assigned to the “1955-1980” group. If the year of the customer was born in is greater than 1980, then they are assigned to the “Over 1980” group. 
There was no participant in the dataset born before 1955. 

Continent
-	The continent of the country in which the participant was born. For example, if the participant’s country of birth was “Thailand”, they would be assigned to Asia. The customer’s country of birth is mapped to their corresponding continent names using country data derived from Wikipedia. 

current_country
-	The current country where the customer resides.

cc_status
-	A binary variable indicating if the customer has the identified gene variant (0-No, 1-Yes).

BMI_group
-	Body Mass Index (BMI) calculated from the customer’s weight in kilograms divided by their height in metres squared. 

n_drink_week_groups
-	The number of alcoholic drinks a customer drinks per week, grouped into the following bands;  '0','1-2','3-5','6-7', '8-10'.

n_cigret_week_groups
-	The number of cigarretes smoked per week, grouped into the following bands; '0','1-10', '11-50', '51-100', '101-200','201-300','Over 300',

edulevel_groups
-	A binary variable with “low_ed” representing customers whos highest level of education attained was 'primary', 'secondary', 'other'  and “high_ed” representing customers who’s highest level of education attained was 'bachelor', 'phD','masters'.

countries_visited_groups
-	The number of countries a customer had visited up until the registration date, grouped into the following categories; '0-5', '6-10','11-30','Over 30'.
