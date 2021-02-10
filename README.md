# World Weather Analysis

Perform requests on the OpenWeather map API and Google Places API to obtain city weather data and hotel information to then display the data in a world map according to preferred weather criteria.

## Business Case

Top travel technology companies, in this case, in the hotel and lodging industry need large amounts of data to collect and present to customers via search web pages.  Clients are enabled with the possibility to filter the search results according to certain parameters.  In the back end, companies use APIs instead of trying to scrape or obtain the data themselves.

In this project, we will use Jupiter notebook and Citypy module to get the cities from more than 500 longitudes and latitudes. Then we will perform requests on the OpenWeather map API and retrieve the JSON weather data from this cities.  The weather data will be added to a Pandas dataframe and mapped using Google Gmaps and the Google Places API.
