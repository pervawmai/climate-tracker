# California Weather Alerts (Active)

```json
{
    "type": "FeatureCollection",
    "features": [
        {
            "event": "Heat Advisory",
            "severity": "Moderate",
            "areaDesc": "San Diego County Coastal Areas; San Bernardino and Riverside County Valleys-The Inland Empire; San Diego County Inland Valleys; Orange County Coastal; Orange County Inland",
            "description": "* WHAT...High temperatures ...",
            "instruction": "Drink plenty of fluids, stay in an air‑conditioned room, ..."
        },
        {
            "event": "Heat Advisory",
            "severity": "Moderate",
            "areaDesc": "Santa Clarita Valley; Ventura County Beaches; ...",
            "description": "* WHAT...Widespread temperatures of 90 to 100 expected.",
            "instruction": "Drink plenty of fluids, stay in an air‑conditioned room, ..."
        }
        // additional alerts omitted for brevity
    ]
}
```

*Data fetched from https://api.weather.gov/alerts/active?area=CA on 2026-03-12.*