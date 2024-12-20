# Air passengers - Data package

This data package contains the data that powers the chart ["Air passengers"](https://ourworldindata.org/grapher/air-passengers-carried?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 18, 2024.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Air transport, passengers carried
Last updated: May 20, 2024  
Next update: May 2025  
Date range: 1970–2021  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Multiple sources compiled by World Bank (2024) – processed by Our World in Data

#### Full citation
Multiple sources compiled by World Bank (2024) – processed by Our World in Data. “Air transport, passengers carried” [dataset]. International Civil Aviation Organization (via World Bank), “World Development Indicators” [original data].
Source: Multiple sources compiled by World Bank (2024) – processed by Our World In Data

### What you should know about this data

### How is this data described by its producer - Multiple sources compiled by World Bank (2024)?
Air passengers carried include both domestic and international aircraft passengers of air carriers registered in the country.

Limitations and exceptions: The air transport data represent the total (international and domestic) scheduled traffic carried by the air carriers registered in a country. Countries submit air transport data to International Civil Aviation Organization (ICAO) on the basis of standard instructions and definitions issued by ICAO. In many cases, however, the data include estimates by ICAO for nonreporting carriers. Where possible, these estimates are based on previous submissions supplemented by information published by the air carriers, such as flight schedules.

The data cover the air traffic carried on scheduled services, but changes in air transport regulations in Europe have made it more difficult to classify traffic as scheduled or nonscheduled. Thus recent increases shown for some European countries may be due to changes in the classification of air traffic rather than actual growth. In the case of multinational air carriers owned by partner States, traffic within each partner State is shown separately as domestic and all other traffic as international.

"Foreign" cabotage traffic (i.e. traffic carried between city-pairs in a State other than the one where the reporting carrier has its principal place of business) is shown as international traffic.

A technical stop does not result in any flight stage being classified differently than would have been the case had the technical stop not been made. For countries with few air carriers or only one, the addition or discontinuation of a home-based air carrier may cause significant changes in air traffic.

Data for transport sectors are not always internationally comparable. Unlike for demographic statistics, national income accounts, and international trade data, the collection of infrastructure data has not been "internationalized."

Statistical concept and methodology: For statistical uses, departures are equal to the number of landings made or flight stages flown. A flight stage is the operation of an aircraft from take-off to its next landing. A flight stage is classified as either international or domestic. International flight stage is one or both terminals in the territory of a State, other than the State in which the air carrier has its principal place of business.

Domestic flight stage is not classifiable as international. Domestic flight stages include all flight stages flown between points within the domestic boundaries of a State by an air carrier whose principal place of business is in that State. Flight stages between a State and territories belonging to it, as well as any flight stages between two such territories, should be classified as domestic. This applies even though a stage may cross international waters or over the territory of another State.

The number of passengers carried is obtained by counting each passenger on a particular flight (with one flight number) once only and not repeatedly on each individual stage of that flight, with a single exception that a passenger flying on both the international and domestic stages of the same flight should be counted as both a domestic and an international passenger.

### Source

#### International Civil Aviation Organization (via World Bank) – World Development Indicators
Retrieved on: 2024-05-20  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


    