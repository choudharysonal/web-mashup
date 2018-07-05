# This web app combines 2 web services: Google maps and Geoname using Javascript and Ajax.
When you click on the map,the app displays postal address and weather at that location.

Used weather service from geonmaes api. Geocoding and reverse geocoding from google maps javascript api.

#Working:
On clicking on the map, you get the address using reverse geocoding. Pass the latitude and longitude to the geonames(findNearByWeatherXML) api to get the weather details.