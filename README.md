![la_skyline](https://github.com/RashidTobrazune/Analyzing_crime_in_Los_Angeles/assets/150378293/61b85c1e-d1d9-45d0-97b5-27bd7d16ad2b)



# Analyzing_crime_in_Los_Angeles
I found out where and when crime is likely to occur, and also the types of crime committed.
Los Angeles, California. The City of Angels. Tinseltown. The Entertainment Capital of the World!

Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. That's where I helped!

I was tasked to support the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. They plan to use my insights to allocate resources effectively to tackle various crimes in different areas.

The Data
They provided me with a single dataset to use. A summary and preview are provided below.

It is a modified version of the original data, which is publicly available from Los Angeles Open Data.

crimes.csv
Column	Description
'DR_NO'	Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.
'Date Rptd'	Date reported - MM/DD/YYYY.
'DATE OCC'	Date of occurrence - MM/DD/YYYY.
'TIME OCC'	In 24-hour military time.
'AREA NAME'	The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. For example, the 77th Street Division is located at the intersection of South Broadway and 77th Street, serving neighborhoods in South Los Angeles.
'Crm Cd Desc'	Indicates the crime committed.
'Vict Age'	Victim's age in years.
'Vict Sex'	Victim's sex: F: Female, M: Male, X: Unknown.
'Vict Descent'	Victim's descent:
A - Other Asian
B - Black
C - Chinese
D - Cambodian
F - Filipino
G - Guamanian
H - Hispanic/Latin/Mexican
I - American Indian/Alaskan Native
J - Japanese
K - Korean
L - Laotian
O - Other
P - Pacific Islander
S - Samoan
U - Hawaiian
V - Vietnamese
W - White
X - Unknown
Z - Asian Indian
'Weapon Desc'	Description of the weapon used (if applicable).
'Status Desc'	Crime status.
'LOCATION'	Street address of the crime.


I analyzed the crime data to guide how they should allocate resources to protect the people of their city! 
I answered the questions using my fndings:


1. Which hour has the highest frequency of crimes? \
   - peak_crime_hour = 1200 hrs.

2. Which area has the largest frequency of night crimes (crimes committed between 10pm and 3:59am)?
   -  peak_night_crime_location= Central

3. Identify the number of crimes committed against victims by age group (0–17, 18–25, 26–34, 35–44, 45–54, 55–64, 65+).

   Victim Ages:
 0-17      4528
18-25    28291
26-34    47470
35-44    42157
45-54    28353
55-64    20169
65+      14747

