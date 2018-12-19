# 311-services-NYCData-EDA
Analysis of 311 services data for a freelancing project

This repository is created for a freelancing project of below tasks.

NYC Boroughs:
1.	Bronx
2.	Manhattan 
3.	Brooklyn
4.	Queens
5.	Staten Island

Data and CSV Schema Fields (can be found from the link below):

https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9


For this project, we are only concerned about 2 fields:

1.	Complaint Types
2.	Borough
3.	Created Date (Should all be from 2017)
4.	Incident Zip




Part A.

1)	Create a script that grabs data from the CSV using the Pandas library.  

i)	Find the 10 most common overall “Complaint types” for the year 2017 from the CSV.  (‘Complaint Type’ is a schema field. )

ii)	Once you have the Complaint Types in part “i”,  ( see numbered list 1-5 above) , how many of each of those 10 types were there in 2017, for each borough? Output a generated CSV with the result.

2)	Find the 10 most populous zip codes.  Extract the list of all unique zip codes in the “Incident_zip” field and match them up with the values from the ‘ZipCode_Population’. 

i)	For each of the 10 zip codes, count the number of complaints per each complaint type.  
ii)	Output a 10 by 10 graph, x-axis is the “Complaint Type” and the y-axis are the zip codes.  We are looking for 100 values.  
iii)	ZipCode_Population.csv (attached to project)
