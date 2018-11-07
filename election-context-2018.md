# Codebook for 2018 Election Analysis Dataset

The data file `election-context-2018.csv` contains demographic and past election data at the county level that can easily be merged with 2018 election returns to analyze the 2018 election. Data for Alaska is not included.

## Variables

### state
- **Description**: state name

----------------

### county
- **Description**: county name

----------------

### FIPS
- **Description**: county FIPS code

----------------

### trump16, clinton16, otherpres16, romney12, obama12, otherpres12
- **Description**: presidential candidate vote totals in 2012 and 2016 (republican, democrat, and non-major party)
- **Year/s**: 2012, 2016
- **Source**: [MEDSL Election Returns Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ)

----------------

### demsen16, repsen16, othersen16, demhouse16, rephouse16, otherhouse16, demgov16, repgov16, othergov16
- **Description**: senate, house, and governor candidate vote totals in 2016 (republican, democrat, and non-major party)
- **Year/s**: 2016
- **Source**: [Stephen Pettigrew Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### repgov14, demgov14, othergov14
- **Description**: governor candidate vote totals in 2014 (republican, democrat, and non-major party)
- **Year/s**: 2014
- **Source**: [Cengiz Zopluoglu](https://sites.education.miami.edu/zopluoglu/2018/11/06/scraping-data-for-2014-gubernatorial-elections/)

----------------

### total\_population
- **Description**: total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### cvap
- **Description**: citizen voting-age population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [Citizen Voting Age Population (CVAP) Special Tabulation From the 2012-2016 5-Year American Community Survey](https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html)

----------------

### white\_pct
- **Description**: non-Hispanic whites as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### black\_pct
- **Description**: non-Hispanic blacks as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### hispanic\_pct
- **Description**: Hispanics or Latinos as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### nonwhite\_pct
- **Description**: non-whites as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### foreignborn\_pct
- **Description**: foreign-born population as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### female\_pct
- **Description**: females as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### age29andunder\_pct
- **Description**: population 29 years or under as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### age65andolder\_pct
- **Description**: population 65 years or older as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### median\_hh\_inc
- **Description**: median household income in the past 12 months (in 2016 inflation-adjusted dollars)
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### clf\_unemploy\_pct
- **Description**: unemployed population in labor force as a percentage of total population in civilian labor force
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### lesshs\_pct
- **Description**: population with an education of less than a regular high school diploma as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### lesscollege\_pct
- **Description**: population with an education of less than a bachelor's degree as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### lesshs\_whites\_pct
- **Description**: white population with an education of less than a regular high school diploma as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### lesscollege\_whites\_pct
- **Description**: white population with an education of less than a bachelor's degree as a percentage of total population
- **Year/s**: 2012-2016 (ACS 5-Year Estimates)
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### rural\_pct
- **Description**: rural population as a percentage of total population
- **Year/s**: 2010
- **Source**: [IPUMS NHGIS, University of Minnesota](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MLLQDH)

----------------

### ruralurban\_cc
- **Description**: rural-urban continuum codes
- **Year/s**: 2013
- **Source**: [USDA Economic Research Service](https://www.ers.usda.gov/data-products/rural-urban-continuum-codes/)
- **Coding**:

| Code | Description |
| --- | --- |
| 1 | Counties in metro areas of 1 million population or more |
| 2 | Counties in metro areas of 250,000 to 1 million population |
| 3 | Counties in metro areas of fewer than 250,000 population |
| 4 | Urban population of 20,000 or more, adjacent to a metro area |
| 5 | Urban population of 20,000 or more, not adjacent to a metro area |
| 6 | Urban population of 2,500 to 19,999, adjacent to a metro area |
| 7 | Urban population of 2,500 to 19,999, not adjacent to a metro area |
| 8 | Completely rural or less than 2,500 urban population, adjacent to a metro area |
| 9 | Completely rural or less than 2,500 urban population, adjacent to a metro area |

-----------------
