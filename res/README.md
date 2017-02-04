# Resources
Contains necessary resources like:
- Bike Sharing Dataset (see [Readme.txt](./Readme.txt) for license)
the datasets [hour.csv](./hour.csv), which contains bike sharing counts aggregated on hourly basis, and [day.csv](./day.csv), which is aggregated on daily basis, have following column descriptions:
  - instant: record index
  - dteday: date
  - season: seasons categorized in 
    1:spring
    2:summer
    3:fall
    4:winter
  - yr: years categories
    0: 2011
    1: 2012
  - mnth: month from 1 through 12
  - holiday: wether day is holiday or not (from [holiday-schedule](http://dchr.dc.gov/page/holiday-schedule))
  - weekday : day of the week
  - workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
  + weathersit : 
    - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
  - temp : Normalized temperature in Celsius. The values are divided to 41 (max)
  - atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
  - hum: Normalized humidity. The values are divided to 100 (max)
  - windspeed: Normalized wind speed. The values are divided to 67 (max)
  - casual: count of casual users
  - registered: count of registered users
  - cnt: count of total rental bikes including both casual and registered
  
  only available in [hour.csv](./hour.csv)
  - hr: hour
