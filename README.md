# weather-underground-data
Weather Underground Data for a set of specific cities. 
The data is presented in CSV files and collected from a weather underground portal manually.
An usefull glossary of columns is available here: https://www.wunderground.com/weather/api/d/docs?d=resources/phrase-glossary

The data comprises the cities:
  - [Bangkok: Bangkok International Airport](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Bangkok&req_statename=Thailand&reqdb.zip=00000&reqdb.magic=313&reqdb.wmo=48456)
  - [Istanbul: Ataturk](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Istanbul&req_statename=Turkey&reqdb.zip=00000&reqdb.magic=131&reqdb.wmo=17060)
  - [Kuala Lumpur: Sultan Abdul Aziz Shah-Subang](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Subang/Sultan%20Abdul%20Azi&req_statename=Malaysia&reqdb.zip=00000&reqdb.magic=392&reqdb.wmo=WWMSA)
  - [London: Heathrow](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=London&req_statename=United%20Kingdom&reqdb.zip=00000&reqdb.magic=108&reqdb.wmo=03772)
  - [Los Angeles: Los Angeles Downtown](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Los%20Angeles&req_state=CA&reqdb.zip=90009&reqdb.magic=22&reqdb.wmo=99999)
  - [New York: Central Park](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=New%20York&req_state=NY&reqdb.zip=10106&reqdb.magic=4&reqdb.wmo=99999)
  - [Paris: Le Bourget](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Paris/Le%20Bourget&req_statename=France&reqdb.zip=00000&reqdb.magic=95&reqdb.wmo=07150)
  - [Rio de Janeiro: Santos Dumont Airport](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Galeao&req_statename=Brazil&reqdb.zip=00000&reqdb.magic=91&reqdb.wmo=83755)
  - [Sao Paulo: Congonhas International ](https://www.wunderground.com/history/airport/SBSP/2016/10/31/DailyHistory.html?req_city=Sao%20Paulo&req_statename=Brazil&reqdb.zip=00000&reqdb.magic=1&reqdb.wmo=83780)
  - [Seoul: Seoul City](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Seoul&req_statename=South%20Korea&reqdb.zip=00000&reqdb.magic=324&reqdb.wmo=47108)
  - [Singapore: Changi](https://www.wunderground.com/history/airport/WSSS/2016/10/31/DailyHistory.html?req_city=Singapore&req_statename=Singapore&reqdb.zip=00000&reqdb.magic=1&reqdb.wmo=48698)
  - [Sydney: Kingsford Smith International](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Sydney&req_statename=Australia&reqdb.zip=00000&reqdb.magic=39&reqdb.wmo=94767)
  - [Tokyo: Tokyo Downtown](https://www.wunderground.com/history/airport//2016/10/31/DailyHistory.html?req_city=Tokyo&req_statename=Japan&reqdb.zip=00000&reqdb.magic=183&reqdb.wmo=47662)

The datasets describe weather variables goruped daily, such as: min, max, avg 
of temperature, humidity, dew point, visilibility (km) wind (km/h), precipitation,
in addition to sea level press. (hPa).

## Seoul Avg. Temperature 
![alt text][sample]

[sample]: https://github.com/leokassio/weather-underground-data/raw/master/images/seoul-uweather.png "Seoul Avg. Temperature - Matplotlib Plot"