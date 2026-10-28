# DS2_clean_proj
A project showcasing my data cleaning skills.

This data was gathered data from Wikipedia and Global Stats. 

Once the data frames were created I renamed the columns so they would be easier to work with. 

The Country column is the key to join the data sets so I cleaned the names in this column for each data set.

The Americas region was split into two regions, North and South America as combining two continents into one region did not seem accurate.

The Caribbean and Central America are added to North America, the subregions were not changed so North and South America are both a region and subregion.

Then I used inner join to join the data so only countries that appeared in each data set would be in the joined data set.

This ensured that there are no missing values, providing a nice data set for visualization and modeling 

The column names in the joined data set are renamed for simplicity and only the necessary columns are selected.

Finally the data in each column is set to its respective data type (numeric or character).



clean_countries variable description

country - Name of the country 

inflation - The annual percentage change in the Consumer Price Index in 2024 

gdp_capita - 2024 GDP per capita, adjusted for purchasing-power difference

pop - The 2023 population in millions from each country as of 2023, sourced form the UN 

per_chg_pop - The percent change in population from 2022 to 2023

region - The continent that contains each nation

subregion - UN defined subregion assigned to each nation


