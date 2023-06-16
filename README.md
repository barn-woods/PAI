# PAI
This file is a template for creating a csv with complete spatial data
for subsiquent load into the dev environment to create shape files with a brake down by year of the data
the example used works with uniform files but the same logic
applies for any system which requires PAI checks.
Marging the complete data allows the complete spatial data to be retained but also adds the brakedown by year
and isolates only the charges relevent to PAI.
Attempting this work manually using excel will likely result in errors as excel will fail to retain the geometry information
in the csv due to the character limit of each cell
