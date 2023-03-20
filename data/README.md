# Data overview
____
## [Download data](https://hb.bizmrg.com/productstar_py-bi-bd/Power%20BI/8.%20%D0%98%D1%82%D0%BE%D0%B3%D0%BE%D0%B2%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82/rideshare_kaggle.csv)
____
### df.shape
(112704, 57)
### df.info()
```
RangeIndex: 112704 entries, 0 to 112703
Data columns (total 57 columns):
     Column                       Non-Null Count   Dtype  

 0   id                           112704 non-null  object 
 1   timestamp                    112704 non-null  float64
 2   hour                         112704 non-null  int64  
 3   day                          112704 non-null  int64  
 4   month                        112704 non-null  int64  
 5   datetime                     112704 non-null  object 
 6   timezone                     112704 non-null  object 
 7   source                       112704 non-null  object 
 8   destination                  112704 non-null  object 
 9   cab_type                     112704 non-null  object 
 10  product_id                   112704 non-null  object 
 11  name                         112704 non-null  object 
 12  price                        103777 non-null  float64
 13  distance                     112704 non-null  float64
 14  surge_multiplier             112704 non-null  float64
 15  latitude                     112704 non-null  float64
 16  longitude                    112704 non-null  float64
 17  temperature                  112704 non-null  float64
 18  apparentTemperature          112704 non-null  float64
 19  short_summary                112704 non-null  object 
 20  long_summary                 112704 non-null  object 
 21  precipIntensity              112704 non-null  float64
 22  precipProbability            112704 non-null  float64
 23  humidity                     112704 non-null  float64
 24  windSpeed                    112704 non-null  float64
 25  windGust                     112704 non-null  float64
 26  windGustTime                 112704 non-null  int64  
 27  visibility                   112704 non-null  float64
 28  temperatureHigh              112704 non-null  float64
 29  temperatureHighTime          112704 non-null  int64  
 30  temperatureLow               112704 non-null  float64
 31  temperatureLowTime           112704 non-null  int64  
 32  apparentTemperatureHigh      112704 non-null  float64
 33  apparentTemperatureHighTime  112704 non-null  int64  
 34  apparentTemperatureLow       112704 non-null  float64
 35  apparentTemperatureLowTime   112704 non-null  int64  
 36  icon                         112704 non-null  object 
 37  dewPoint                     112704 non-null  float64
 38  pressure                     112704 non-null  float64
 39  windBearing                  112704 non-null  int64  
 40  cloudCover                   112704 non-null  float64
 41  uvIndex                      112704 non-null  int64  
 42  visibility.1                 112704 non-null  float64
 43  ozone                        112704 non-null  float64
 44  sunriseTime                  112704 non-null  int64  
 45  sunsetTime                   112704 non-null  int64  
 46  moonPhase                    112704 non-null  float64
 47  precipIntensityMax           112704 non-null  float64
 48  uvIndexTime                  112704 non-null  int64  
 49  temperatureMin               112703 non-null  float64
 50  temperatureMinTime           112703 non-null  float64
 51  temperatureMax               112703 non-null  float64
 52  temperatureMaxTime           112703 non-null  float64
 53  apparentTemperatureMin       112703 non-null  float64
 54  apparentTemperatureMinTime   112703 non-null  float64
 55  apparentTemperatureMax       112703 non-null  float64
 56  apparentTemperatureMaxTime   112703 non-null  float64
dtypes: float64(33), int64(13), object(11)
```
### Columns used
1. cab_type
2. cloudCover
3. datetime
4. destination
5. distance
6. humidity
7. latitude
8. longitude
9. moonPhase
10. name
11. pressure
12. price
13. short_summary
14. source
15. surge_multiplier
16. temperature
17. visibility
18. windSpeed
