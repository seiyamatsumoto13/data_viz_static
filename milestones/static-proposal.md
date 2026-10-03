# Seiya Matsumoto

## Description

I want to explore how economic growth and prosperity have been distributed across the United States, with a particular focus on labor income and economic inequality.

My goal is to investigate how income inequality has developed within the U.S. economic system and whether it has intensified over time. I particularly plan to visualize long-term changes in income inequality and differences across demographic and geographic groups.

The project will begin with the long-term development of income inequality in the United States and then examine who earns income and how these patterns differ across demographic groups and geographic areas. Ultimately, I hope to explore whether the contemporary U.S. economy distributes economic gains broadly or increasingly concentrates them among higher-income groups.


## Data Sources

### Data Source 1: U.S. Census Bureau — Current Population Survey Annual Social and Economic Supplement (CPS ASEC)

URL: https://www.census.gov/data/datasets/time-series/demo/cps/cps-asec.html

Size: The 2026 CPS ASEC person-level CSV contains **134,729 rows and 831 columns**. I plan to select approximately 15–30 variables related to income, employment, and demographics. I may also use selected earlier annual files to examine long-term changes while keeping each working dataset within a manageable size.

Description:

CPS ASEC provides detailed person-level information on income, earnings, employment, and demographic characteristics. Historical annual files are also available, making it possible to investigate changes in the distribution of income over time.

I explored the 2026 person-level CSV file and confirmed that it contains 134,729 individual records and 831 variables. Since the complete dataset contains substantially more variables than are necessary for this project, I plan to create smaller subsets containing variables relevant to earnings, employment, and demographic characteristics.

I plan to use selected years of CPS ASEC to examine changes in income inequality and differences across demographic groups. In particular, I am interested in comparing labor earnings across income groups and investigating whether income has become increasingly concentrated over time.

### Data Source 2: U.S. Census Bureau — American Community Survey Public Use Microdata Sample (ACS PUMS)

URL: https://api.census.gov/data/2024/acs/acs1/pums.html

Size: The full 2024 ACS 1-Year PUMS contains millions of person-level observations and 524 available variables. Because the complete national dataset is larger than necessary for this project, I plan to use the Census Microdata API to select approximately 15–30 variables and a geographic subset, keeping the working dataset below approximately 1 million observations.

Description:

ACS PUMS provides individual- and household-level microdata on wages, income, employment, occupation, education, demographic characteristics, and geography. The data include geographic identifiers such as state and Public Use Microdata Area (PUMA).

I explored the 2024 PUMS variable documentation and found variables relevant to income, wages, employment, occupation, education, and demographic characteristics. Rather than downloading the entire national dataset, I plan to use the Census Microdata API to retrieve only the observations and variables needed for the project.

I plan to use ACS PUMS primarily to investigate how labor income and economic inequality differ across demographic and geographic groups. The geographic identifiers may also allow me to visualize the spatial distribution of economic inequality and compare patterns across different parts of the United States.

Together, CPS ASEC and ACS PUMS should allow me to connect long-term changes in U.S. income inequality with more detailed contemporary patterns in labor income, demographics, and geography.


## Questions

1. Is the scope of connecting long-term income inequality with demographic and geographic differences appropriate for the static visualization project, or would you recommend narrowing the focus?

2. Is it appropriate to use selected years and variables from CPS ASEC rather than every available year in order to keep the amount of data manageable?

3. For ACS PUMS, is using the API to create a geographic and variable subset an appropriate approach for keeping the dataset within the recommended size range?
