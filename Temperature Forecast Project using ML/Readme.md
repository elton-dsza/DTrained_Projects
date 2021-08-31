# Temperature Forecast Project using ML
## Problem Statement:
### <b>Data Set Information:</b>

This data is for the purpose of bias correction of next-day maximum and minimum air temperatures forecast of the LDAPS model operated by the Korea Meteorological Administration over Seoul, South Korea. This data consists of summer data from 2013 to 2017. The input data is largely composed of the LDAPS model's next-day forecast data, in-situ maximum and minimum temperatures of present-day, and geographic auxiliary variables. There are two outputs (i.e. next-day maximum and minimum air temperatures) in this data. Hindcast validation was conducted for the period from 2015 to 2017.
<br><br><br>

### <b>Attribute Information:</b><br><br><br>

For more information, read [Cho et al, 2020].<br><br>
- station - used weather station number: 1 to 25
- Date - Present day: yyyy-mm-dd ('2013-06-30' to '2017-08-30')
- Present_Tmax - Maximum air temperature between 0 and 21 h on the present day (Â°C): 20 to 37.6
- Present_Tmin - Minimum air temperature between 0 and 21 h on the present day (Â°C): 11.3 to 29.9
- LDAPS_RHmin - LDAPS model forecast of next-day minimum relative humidity (%): 19.8 to 98.5
- LDAPS_RHmax - LDAPS model forecast of next-day maximum relative humidity (%): 58.9 to 100
- LDAPS_Tmax_lapse - LDAPS model forecast of next-day maximum air temperature applied lapse rate (Â°C): 17.6 to 38.5
- LDAPS_Tmin_lapse - LDAPS model forecast of next-day minimum air temperature applied lapse rate (Â°C): 14.3 to 29.6
- LDAPS_WS - LDAPS model forecast of next-day average wind speed (m/s): 2.9 to 21.9
-  LDAPS_LH - LDAPS model forecast of next-day average latent heat flux (W/m2): -13.6 to 213.4
-  LDAPS_CC1 - LDAPS model forecast of next-day 1st 6-hour split average cloud cover (0-5 h) (%): 0 to 0.97
-  LDAPS_CC2 - LDAPS model forecast of next-day 2nd 6-hour split average cloud cover (6-11 h) (%): 0 to 0.97
-  LDAPS_CC3 - LDAPS model forecast of next-day 3rd 6-hour split average cloud cover (12-17 h) (%): 0 to 0.98
-  LDAPS_CC4 - LDAPS model forecast of next-day 4th 6-hour split average cloud cover (18-23 h) (%): 0 to 0.97
-  LDAPS_PPT1 - LDAPS model forecast of next-day 1st 6-hour split average precipitation (0-5 h) (%): 0 to 23.7
-  LDAPS_PPT2 - LDAPS model forecast of next-day 2nd 6-hour split average precipitation (6-11 h) (%): 0 to 21.6
-  LDAPS_PPT3 - LDAPS model forecast of next-day 3rd 6-hour split average precipitation (12-17 h) (%): 0 to 15.8
-  LDAPS_PPT4 - LDAPS model forecast of next-day 4th 6-hour split average precipitation (18-23 h) (%): 0 to 16.7
-  lat - Latitude (Â°): 37.456 to 37.645
-  lon - Longitude (Â°): 126.826 to 127.135
-  DEM - Elevation (m): 12.4 to 212.3
-  Slope - Slope (Â°): 0.1 to 5.2
-  Solar radiation - Daily incoming solar radiation (wh/m2): 4329.5 to 5992.9
-  Next_Tmax - The next-day maximum air temperature (Â°C): 17.4 to 38.9
-  Next_Tmin - The next-day minimum air temperature (Â°C): 11.3 to 29.8T

<b>Please note that there are two target variables here: </b><br><br>
<font style="color:red;">
- Next_Tmax: Next day maximum temperature

- Next_Tmin: Next day  minimum temperature
</font>
<br><br><br>

<b>Note: Use the link below to download the dataset. </b>
<br><br>
Downlaod Files:<br>
https://github.com/dsrscientist/Dataset2/blob/main/temperature.csv
