
1.	What is the maximum number of non family households in the median year 1939?

SELECT max(nonfamily_households) as max_no_household FROM `bigquery-public-data.census_bureau_acs.blockgroup_2010_5yr` 
where median_year_structure_built = 1939.0

