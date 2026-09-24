# New cases of malaria per 1,000 people at risk - Data package

This data package contains the data that powers the chart ["New cases of malaria per 1,000 people at risk"](https://ourworldindata.org/grapher/incidence-of-malaria?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on September 18, 2026.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV structure

Each row is an observation for an entity (usually a country or region) at a timepoint.

- "Entity" — the name of the entity, e.g. "United States".
- "Code" — our internal entity code. For most countries this is the [ISO alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code, e.g. "USA"; historical and other non-standard entities get a custom code.
- "Year" or "Day" — the timepoint. Annual data has a "Year" column holding an integer year; otherwise a "Day" column holds a date string in the form "YYYY-MM-DD".
- The final column is the data column — the time series that powers the chart. Downloaded with the "full data" option it corresponds to the time series below; with "only selected data visible in the chart" it is transformed depending on the chart type, so the correspondence may be less direct.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc.

## How we process data at Our World in Data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stitch together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

Preparing this data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/).

## Detailed information about the data


### Incidence of malaria (per 1,000 population at risk)
Last updated: July 27, 2026  
Next expected update: January 2027  
Date range: 2000–2024  
Unit: per 1,000 population at risk  
Source: World Health Organization (Global Health Observatory), via World Bank (2026) – processed by Our World in Data  

#### How to cite this data

World Health Organization (Global Health Observatory), via World Bank (2026) – processed by Our World in Data

#### How this data is described by its producers
Incidence of malaria is the number of new cases of malaria in a year per 1,000 population at risk.

### Aggregation method:
Weighted average

### Statistical concept and methodology:
Methodology: Confirmed malaria cases for countries and areas outside Africa, and for low-transmission countries and areas in Africa are adjusted for extent of health service use (treatment seeking), underreporting and lack of case confirmation (the likelihood that cases are parasite positive). In high transmission areas in which the quality of surveillance data does not permit a robust estimate from the number of reported cases, but good data on parasite prevalence is available, the number of cases can be estimated from parasite prevalence. The denominator is estimated, using official UN population and population at risk estimates for countries with sub-national endemicity.
Statistical concept(s): Complete data on malaria cases reported through surveillance systems are the best source of data but are rarely available for large populations at high quality and accuracy. Reported data on malaria cases generally need to be adjusted for extent of health service use (treatment seeking), underreporting and lack of case confirmation (the likelihood that cases are parasite positive). WHO compiles data on reported confirmed cases of malaria and suspected cases tested with microscopy or RDT, submitted by national malaria control programmes. Underreporting is reported or estimated by countries. The extent of health service use (treatment seeking) data were obtained from nationally representative household surveys on health service use.

### Development relevance:
Malaria is a life-threatening disease caused by parasites that are transmitted to people through the bites of infected female Anopheles mosquitoes. It is preventable and curable. There are 5 parasite species that cause malaria in humans, and 2 of these species – Plasmodium falciparum and Plasmodium vivax – pose the greatest threat.

### Other notes:
This is the Sustainable Development Goal indicator 3.3.3[https://unstats.un.org/sdgs/metadata/].


## Sources

These are the sources behind the data in this package. Each time series above names the ones it draws on in its citation.

### World Health Organization (Global Health Observatory), via World Bank – World Development Indicators

The World Development Indicators (WDI) database, published by the World Bank, is a comprehensive collection of global development data, providing key economic, social, and environmental statistics. It includes over 1,500 indicators covering more than 200 countries and territories, with data spanning several decades. WDI serves as a vital resource for policymakers, researchers, businesses, and analysts seeking to understand global trends and make data-driven decisions. The database covers a wide range of topics, including economic growth, education, health, poverty, trade, energy, infrastructure, governance, and environmental sustainability. The indicators are sourced from reputable national and international agencies, ensuring high-quality, consistent, and comparable data. Users can access the database through interactive online tools, API services, and downloadable datasets, facilitating detailed analysis and visualization. WDI is also used for tracking progress on the Sustainable Development Goals (SDGs) and other global development initiatives. By providing accessible and reliable statistics, it helps to inform policy discussions and strategies globally. Whether for academic research, policy planning, or economic analysis, the World Development Indicators database is an essential tool for understanding and addressing global development challenges.

Producer: World Health Organization (Global Health Observatory), via World Bank  
Published: 2026-07-15  
Retrieved on: 2026-07-27  
Retrieved from: https://data.worldbank.org/indicator/SH.MLR.INCD.P3  
Direct download: https://databankfiles.worldbank.org/public/ddpext_download/WDI_CSV.zip  
License: CC BY 4.0 (https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators)  

Citation: Global Health Observatory Data Repository/World Health Statistics, World Health Organization (WHO), uri: http://apps.who.int/ghodata/. Indicator SH.MLR.INCD.P3 (https://data.worldbank.org/indicator/SH.MLR.INCD.P3). World Development Indicators – World Bank (2026). Accessed on 2026-07-27.

    