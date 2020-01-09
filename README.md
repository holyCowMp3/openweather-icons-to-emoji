# openweather-icons-to-emoji
Simple json to convert [Openweather icons](https://openweathermap.org/weather-conditions) to emoji, acceptable in CLI, or text representation
# Usage
For using in different languages just import json, and retrieve value from map
# JavaScript

```
const icons = require("./icons.json");
var emoji_icon = icons['01d'] //return emoji equal to 01d - clear sky ☀

```
# Python

``` 
import json
with open('icons.json', 'r') as f:
	icons = json.load(f)
emoji_icon = icons['01d'] #return emoji equal to 01d - clear sky ☀

```
