```json
{
    "@context": [
        "https://geojson.org/geojson-ld/geojson-context.jsonld",
        {
            "@version": "1.1",
            "wx": "https://api.weather.gov/ontology#",
            "geo": "http://www.opengis.net/ont/geosparql#",
            "unit": "http://codes.wmo.int/common/unit/",
            "@vocab": "https://api.weather.gov/ontology#"
        }
    ],
    "type": "Feature",
    "properties": {
        "units": "us",
        "forecastGenerator": "BaselineForecastGenerator",
        "generatedAt": "2026-03-13T01:38:28+00:00",
        "updateTime": "2026-03-12T20:25:59+00:00",
        "validTimes": "2026-03-12T14:00:00+00:00/P7DT14H",
        "periods": [
            {
                "number": 1,
                "name": "Tonight",
                "startTime": "2026-03-12T18:00:00-07:00",
                "endTime": "2026-03-13T06:00:00-07:00",
                "isDaytime": false,
                "temperature": 52,
                "temperatureUnit": "F",
                "windSpeed": "7 mph",
                "windDirection": "W",
                "shortForecast": "Partly Cloudy",
                "detailedForecast": "Partly cloudy, with a low around 52. West wind around 7 mph."
            },
            {
                "number": 2,
                "name": "Friday",
                "startTime": "2026-03-13T06:00:00-07:00",
                "endTime": "2026-03-13T18:00:00-07:00",
                "isDaytime": true,
                "temperature": 70,
                "temperatureUnit": "F",
                "windSpeed": "2 to 8 mph",
                "windDirection": "W",
                "shortForecast": "Mostly Sunny",
                "detailedForecast": "Mostly sunny. High near 70, with temperatures falling to around 67 in the afternoon. West wind 2 to 8 mph."
            },
            {
                "number": 3,
                "name": "Friday Night",
                "startTime": "2026-03-13T18:00:00-07:00",
                "endTime": "2026-03-14T06:00:00-07:00",
                "isDaytime": false,
                "temperature": 52,
                "temperatureUnit": "F",
                "windSpeed": "8 mph",
                "windDirection": "W",
                "shortForecast": "Partly Cloudy",
                "detailedForecast": "Partly cloudy, with a low around 52. West wind around 8 mph."
            }
        ]
    }
}
```