# Where to open a new coffee shop project ??
##  📖 Background :
You are helping a client who owns coffee shops in Colorado. The company's coffee shops serve high-quality and responsibly sourced coffee, pastries, and sandwiches. They operate three locations in Fort Collins and want to expand into Denver. Your client believes that the ideal location for a new store is close to affluent households, and the store appeals to the 20-35 year old demographic. Your team collected geographical and demographic information about Denver's neighborhoods to assist the search. They also collected data for Starbucks shops in Denver. Starbucks and the new coffee shops do not compete for the same clients; the team included their location as a reference.
## 💪 Your challenge :
Provide your client a list of neighborhoods in Denver where they should consider expanding. Include:

- A visualization of Denver's neighborhoods and the Starbucks store locations.

- Find the neighborhoods with the highest proportion of people in the target demographic.

- Select the top three neighborhoods where your client should focus their search.

## 💾 The data
You have assembled information from three different sources ([locations](https://github.com/chrismeller/), [neighborhoods](http://data.denvergov.org), [demographics](https://www.census.gov/)):

#### Starbucks locations in Denver, Colorado
- "StoreNumber" - Store Number as assigned by Starbucks
- "Name" - Name identifier for the store
- "PhoneNumber" - Phone number for the store
- "Street 1, 2, and 3" - Address for the store
- "PostalCode" - Zip code of the store
- "Longitude, Latitude" - Coordinates of the store

#### Neighborhoods' geographical information
- "NBHD_ID" - Neighborhood ID (matches the census information)
- "NBHD_NAME" - Name of the statistical neighborhood
- "Geometry" - Polygon that defines the neighborhood

#### Demographic information
- "NBHD_ID" - Neighborhood ID (matches the geographical information)
- "NBHD_NAME' - Nieghborhood name
- "POPULATION_2010' - Population in 2010
- "AGE_ " - Number of people in each age bracket (< 18, 18-34, 35-65, and > 65)
- "NUM_HOUSEHOLDS" - Number of households in the neighborhood
- "FAMILIES" - Number of families in the neighborhood
- "NUM_HHLD_100K+" - Number of households with income above 100 thousand USD per year

_Starbucks locations were scrapped from the Starbucks store locator webpage by [Chris Meller](https://github.com/chrismeller/)._  
_Statistical Neighborhood information from the [City of Denver Open Data Catalog](http://data.denvergov.org), [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) license._      
_Census information from the [United States Census Bureau](https://www.census.gov/). Publicly available information._


# Note ❗❗❗

This project is my participation in Data camp Competition called : "Where to open a new coffee shop?".

link of Competition: https://app.datacamp.com/learn/competitions/denver-coffee-shop

link of my  publication : https://app.datacamp.com/workspace/w/a6b7aab1-c9cf-4fbb-a244-ff8234db073b
