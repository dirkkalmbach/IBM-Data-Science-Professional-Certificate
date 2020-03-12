# Data Understanding

>Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data.

## Description of the Data
Income data about the neighbourhoods _("how wealthy is this neighbourhood?")_, general geo location data about Toronto and location data about venues in Toronto will be used to answer the question wether a location is profitable to start a business or not. The question will be answered for any business which exists as a venue category on Foursquare. 
Foursquare Data consists of geo codes (longitudes and latitudes) and veneue categories (e.g.: "italian restaurant"). Toronto Neighbourhood Data defines the boundary for the final product: venues only within the city boundary of Toronto will be considered. This data gives also everage income per houshold on a neighbourhood level.

## Deployment
The final to deployable product should consist of an interactive web site which allows users to chose a veneue category from a list. An interactive map of Toronto will show then 1-3 possible locations for the new venue/business location.
Optionally, he can filter the map by other categories like minimum average income of the neighbourhood.

## Data Sources
- [Toronto Neighbourhood Profiles](https://open.toronto.ca/dataset/neighbourhood-profiles/), direct link to datasets I used (accessed: 2020-03-06):
	- [neighbourhood-profiles-2016-csv](https://ckan0.cf.opendata.inter.prod-toronto.ca/download_resource/ef0239b1-832b-4d0b-a1f3-4153e53b189e?format=csv)
	- [neighbourhood-profiles-2016-readme](https://ckan0.cf.opendata.inter.prod-toronto.ca/download_resource/bae6a4f1-09f2-44c6-8567-8ee28603c5cf?format=csv)
- [Foursquare API Data](https://developer.foursquare.com/docs)
- [List of postal codes of Canada (wikipedia)](https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)