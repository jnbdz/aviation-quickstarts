<img src="assets/weather.webp" alt="Aviation weather" style="width: 380px;" align="right">

# Weather | Aviation | Quickstarts

## Terms
- METAR - Meteorological Aerodrome Report - A regular scheduled weather report that usually comes out once every hour
- SPECI - Special Weather Report - An unschedule weather report that comes out between the hourly METARs - For when we have bad weather or rapidly changing weather
### Surface Observation Format
- Airfield Name
- Date/Time
- Wind
- Visibility
- Significant Weather
- Clouds/Ceilings
- Temperature/Dewpoint
- Altimeter
- Remarks

> WARNING! Some of this information is not required
> 
> Like: 
> - Significant Weather
> - Dewpoint
> - Remarks

#### Exemple
- KTUL 250153Z 04011KT 10SM SCT250 08/01 RMK AO2 SPL143 T00780006
  - KTUL - Airport identifier
  - 250153Z - Date and Time in Zulu - 
    - 25 - Day of the month
    - 01 - Hour
    - 53 - Minute
    - Z - Depending if this is 

## Airport Identifier Codes
- USA - They all start with `K` followed by 3 digits (K XXX)
  - Alaska and Hawaii it is `P` followed by 3 digits
- Canada `C` followed by 3 digits (C XXX) (e.g.: CYUL)

## Clouds
### Cloud types
![](./assets/Cloud_types_en.svg)

> The list of cloud types groups all genera as high (cirro-, cirrus), middle (alto-), multi-level (nimbo-, cumulo-, cumulus), and low (strato-, stratus).
*Source: https://en.wikipedia.org/wiki/List_of_cloud_types*

#### Cumulonimbus
Also refered as: 
- thunderheads

##### Etymology: 
From the Latin words: 
- *cumulus*: "heaped"
- *nimbus*: "rainstorm"

##### Aspects
###### Qualities:
- dense
- towering vertical

###### Forming:
- from *water vapor* carried by powerful upward air currents
- can form alone or along cold front [squall lines](https://en.wikipedia.org/wiki/Squall_line)

###### Produce:
- can produce lightning
- other dangerous sever weather
   - tornadoes
   - hailstones
   - and more...

## Command Line
- [wttr](http://wttr.in)
- More to come...

## Resources
- [Aviation Weather Center (GFA) (interactive weather map) (all countries) | AviationWeather.gov](https://aviationweather.gov/gfa/#obs)
- [UBC ATSC 113 - Cloud Coverage](https://www.eoas.ubc.ca/courses/atsc113/flying/met_concepts/01-met_concepts/01c-cloud_coverage/index.html)
- [AWWS - Weather code and symbols legend](https://flightplanning.navcanada.ca/cgi-bin/CreePage.pl?Langue=anglais&NoSession=NS_Inconnu&Page=wxsymbols&TypeDoc=wxsymb)
- [Cloud Types [img]](https://i.imgur.com/apMxFFz.jpg)
- Videos: 
  - [Cloud Type | Youtube Video](https://www.youtube.com/watch?v=oVkECR387gQ)
  - [Weather BASICS explained (EASY to Understand) PPL Lesson 39 | Youtube Video](https://www.youtube.com/watch?v=A4eIGJrntXg)
