# COVID-19 and Vaccinations in North America
Dave Wisinski
----
April 2021
----
----

## Purpose/Proposal

The purpose of the project is to uncover patterns and relationships in the COVID-19 dataset within and relative to North America.

## Source Data

Max Roser, Hannah Ritchie, Esteban Ortiz-Ospina and Joe Hasell (2020) - "Coronavirus Pandemic (COVID-19)". Published online at OurWorldInData.org. Retrieved from: 'https://ourworldindata.org/coronavirus' [Online Resource].

https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv

**Data used last updated 4/2/21.**

## Limtations

The primary limitations of this data set will be:

- Recency: As the global availability of COVID-19 vaccinations and the subsequent respective distribution schedules will be evolving very rapidly, some of the more recent data may experience a lag in reporting which will have a minor effect on some of the analyses.

- Missing data: The availability of certain data paramaters/values may not be consistent across continents and countries for a variety of reasons (demographic, political, technological, etc.). For this reason not all countries will be included in all analyses these limitations will affect which countries have reported relevant data for some of the analyses. 

## Findings

- Human Development Index vs. Confirmed COVID-19 Cases:

    There is a relatively weak positive correlation between North Ameican countries' respective [Human Development Indexes](http://hdr.undp.org/en/content/human-development-index-hdi) (recorded on scale from zero to one) and the confirmed* COVID-19 cases for those countries. For example, Canada and the United States, the countries with the first and second highest HDIs, have the first and fifth highest report case totals; Haiti, the lowest on the HDI scale, has the third lowest confirmed case total from the same group. Population density for each country likewise appears to have little bearing on confirmed cases, though this may be subject to the same limitations discussed above relating to limited reporting capabilities, etc. in various countries.

    \* Note: confirmed cases may be much lower than actual cases, as confirmed cases only represent confirmed positive tests reported to the government reporting body of each country. In the US for example, recent [machine learning models estimate total actual COVID-19 cases to date are about 2-3x higher](https://www.utsouthwestern.edu/newsroom/articles/year-2021/covid-19-infections-in-the-us-nearly-three-times-greater-than-reported.html) than reported cases alone.

- Total Vaccine Doses Administered:

    North America trails only Asia in recent vaccine doses administered, primarily due to the swift scaling of distribution in the US. Proportionally to overall population, North America is administering vaccinations much faster than all other continents (in this example for instance, in North America during the period examined four doses were administered per 100 people in the overall population; in Asia less than one dose per 100 people was administered).

- Average Stringencty Index and Percentage of Population Vaccinated**

    A country's [Stringency Index](https://ourworldindata.org/covid-government-stringency-index) (reported on a scale of zero to 100) can be considered to be an aggregate of the strictness of lockdown measures implemented by the government of that country. For this analysis, the average stringency index over the entire reporting period of the dataset was taken (blank or non-reported index values were ignored rather than treated as a 0). In this example, the United States ranks tenth on the Stringency Index list, with an average value just over 61, in-line with Canada just ahead of it. For reference, the leader in Stringency is Honduras with an average index value of just under 88.

    High Stringency Index values do not tend to correlate with population vaccination percentages. This may indicate that attempted preventative measures have generally been more straightforward to implement vs. implementation of a vaccine distribution and administration on a national scale.

- GDP per Capita and Percentage of Population Vaccinted**

    There is a strong positive correlation between North American countries' [GDP per Capita](https://databank.worldbank.org/metadataglossary/world-development-indicators/series/NY.GDP.PCAP.KN) and the respective percentage of population which has been vaccinated. This would appear to be relatively rational as it can be presumed that countries with greater economic health likely have better infrastructure, generally better access to the healthcare resources necessary to facilitate vacciations, more stable political environments, etc.


    \** Percentage of population vaccinated represents the percentage of the population which has received at least one vaccination dose, irrespective of whether the treatment regimen includes multiple doses.



