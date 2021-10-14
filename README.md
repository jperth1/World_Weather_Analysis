# World_Weather_Analysis

## Overview of World Weather Analysis

This repository performs three actions in efforts to present a potential travel itinerary based on the preference of the traveler.  The three actions are as follows:

1. Retrieve weather data for 2,000 randomly generated latitudes and longitudes, retrieve the nearest city to these coordinates, and perform an API call with the OpenWeatherMap to display relevant weather data for those cities in a DataFrame.
2. Create a customer travel destinations map using input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels, which is shown in DataFrame and a marker layer map with pop-up markers using Google Near By Search and Directions API.
3. Create a travel itinerary map of four potential cities that meet the traveler's weather preferences using Google Directions API.

![WeatherPy_travel_map_markers](/Weather_Database/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

## Resources

- Software: Python 3.9.1, Jupyter Notebook 6.1.4
- API: OpenWeatherMap, Google 

## Recommendations

The travel locations presented in this analysis includes four cities in Indonesia. The first stop in this trip is Bengkulu followed by Bambanglipuro, Denpasar, Bima and then ending back in Bengkulu. This itinerary was specifically created for the traveler to visit five UNESCO World Heritage sites closely located to the four cities chosen. 

The first city, Bengkulu, closely located to the Tropical Rainforest Heritage of Sumatra, which includes three national parks which hold beautiful senary, extensive biodiversity and endangered species.  

The second city, Bambanglipuro about an hour’s drive to two beautiful UNESCO World Heritage sites, Borobudur Temple Compounds and Prambanan Temple Compounds. Both of these sites are home to magnificent Hindu temples and beautiful ancient architecture constructed between 8th and 10th century AD.

The third city, Denpasar, is located on the island of Bali. The whole island of Bali has been made a UNESCO World Heritage site as its truly a unique and magnificent landscape. It has beautiful beach, a tropical environment, and famous rice terraces that will amaze any visitor.

Finally, Bima is a short ferry ride away from Komodo National Park which is home to giant lizards, called 'Komodo dragons'. The giant Komodo lizards exist nowhere else in the world and are truly an incredible and unique species. The Komodo National Park is a once in a lifetime experience that will leave any visitor in awe and excitement.
