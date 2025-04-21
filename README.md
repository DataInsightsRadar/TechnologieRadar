# TechnologieRadar Prompt`s
1. Prompt:

*General Context:* 
The question is related to the company called NORD/LB based in Niedersachsen, Germany.
NORD/LB is one of the leading German commercial banks. 
As an institute under public law, it is part of the S-Finance Group and is one of the nationally system-relevant banks in Germany.
The question is further related to a department in the NORD/LB that is responsible for data awareness and responsibility, 
data governance, establishing standards and optimize data driven processes in context of long living datamanagement.
*Task description:*
The goal is to create a table with information for a technology radar from `ThoughtWorks`.
Generate the table that contains relevant technologies, tools, events located in germany and potential company partners that are relevant for the mentioned department.
Main topics are: 
- Datamanagement
- Digitalization
- Financial markets
Focus on the datamanagement role.
*Table format:*
Each row of the table must contain the following columns:
- *name*
-*ring* - (Adopt, Trial, Assess, Hold)
- *quadrant* - One of `Techniques`, `Tools`, `Platforms`, `languages-and-frameworks`. Use `Platforms` to indicate events. Use `languages-and-frameworks` to indicate potential partner companies.
- *isNew* - One of `TRUE`, `FALSE`. Indicates weather the information is new and not already present in a previous radar
- *status* - One of `new` (added information), `no change` (untouched information), `moved in` (information that is moved from one quadrant to another)
- *description* - A detailed description. The description must contain source links formatted in HTML5. Write the description in German.
Dont alter the column names in any way.
The table should contain at least 20 entries.

2. Prompt:

Convert the spreadsheet into a CSV file and provide a direct download link.
