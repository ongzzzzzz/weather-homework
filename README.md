# Hi!

This is a project where you get to implement / learn how to build an interactive PWA. Head over to `script.js` for more technical details.

### Materials Needed:
- A free API Key from `https://openweathermap.org/price`

### The general flow of our app would look like this:

1. User opens app.
2. User clicks a button.
3. Geolocation data is fetched. ([Reference](https://repl.it/@Fogeinator/gpspwa6feb2021#script.js))
4. Weather data is fetched. ([API Sauce](https://openweathermap.org/current#geo))
5. User can see the current weather conditions on the page.

#### What do I fetch, actually?
⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇
```json
"weather": [
	{
		"id": 800,
		"main": "Clear",
		"description": "clear sky",
		"icon": "01n"
	}
],
```
```json
"main": {
	"temp": 281.52,
	"feels_like": 278.99,
	"temp_min": 280.15,
	"temp_max": 283.71,
	"pressure": 1016,
	"humidity": 93
},
```

#### Where did you get that JSON data from? 
idk but i know the link's in this document somewhere. you'd need some `Ctrl + F` and some scrolling.

#### Additional:
Read [here](https://openweathermap.org/weather-conditions#How-to-get-icon-URL) to get the img icon for different weather conditions ;)

# Questions? 
Ask in messenger :D