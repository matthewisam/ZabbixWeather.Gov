# ZabbixWeather.Gov
A Zabbix plugin for weather data from weather.gov api

  #Installation
- Install like any other template (import)
- Make a new host and link the template
- Add a macro named: {$STATION} and set the value to the four letter station code eg KDCA for Washington/Reagan National Airport, DC
- Important: Edit the template item named "Get Gov weather" and change the Headers to whatever you want. If we all use the same user agent value we could be banned or rate limited. The suggested info on the API site is a short description and your contact info incase there is a problem.
