```json
{
    "@context": [
        "https://geojson.org/geojson-ld/geojson-context.jsonld",
        {
            "@version": "1.1",
            "wx": "https://api.weather.gov/ontology#",
            "@vocab": "https://api.weather.gov/ontology#"
        }
    ],
    "type": "FeatureCollection",
    "features": [
        {
            "id": "https://api.weather.gov/alerts/urn:oid:2.49.0.1.840.0.a68fcf9bedf21fe106903c65ccf2638ca407a494.002.1",
            "type": "Feature",
            "geometry": null,
            "properties": {
                "@id": "https://api.weather.gov/alerts/urn:oid:2.49.0.1.840.0.a68fcf9bedf21fe106903c65ccf2638ca407a494.002.1",
                "@type": "wx:Alert",
                "id": "urn:oid:2.49.0.1.840.0.a68fcf9bedf21fe106903c65ccf2638ca407a494.002.1",
                "areaDesc": "San Luis Obispo County Beaches; San Luis Obispo County Inland Central Coast; Santa Lucia Mountains; Santa Barbara County Central Coast Beaches; Santa Barbara County Inland Central Coast; Santa Ynez Valley; Santa Barbara County Southwestern Coast; Santa Barbara County Southeastern Coast; Santa Ynez Mountains Western Range; Santa Ynez Mountains Eastern Range",
                "severity": "Moderate",
                "event": "Heat Advisory",
                "headline": "Heat Advisory issued March 12 at 1:22PM PDT until March 13 at 8:00PM PDT by NWS Los Angeles/Oxnard CA",
                "description": "* WHAT...Temperatures of 85 to 95 expected.\n\n* WHERE...San Luis Obispo County Beaches, San Luis Obispo County Inland Central Coast, Santa Barbara County Central Coast Beaches, Santa Barbara County Inland Central Coast, Santa Barbara County Southeastern Coast, Santa Barbara County Southwestern Coast, Santa Lucia Mountains, Santa Ynez Mountains Eastern Range, Santa Ynez Mountains Western Range, and Santa Ynez Valley.\n\n* WHEN...Until 8 PM PDT Friday.\n\n* IMPACTS...There is a high risk for heat illness for sensitive populations including the very young, the very old, those without air conditioning, and those active outdoors.\n\n* ADDITIONAL DETAILS...Well above normal temperatures will continue well into next week, and additional Heat Advisories or Extreme Heat Warnings may be needed.",
                "instruction": "Drink plenty of fluids, stay in an air-conditioned room, stay out of the sun, and check up on relatives and neighbors."
            }
        },
        {
            "id": "https://api.weather.gov/alerts/urn:oid:2.49.0.1.840.0.a68fcf9bedf21fe106903c65ccf2638ca407a494.001.1",
            "type": "Feature",
            "geometry": null,
            "properties": {
                "@id": "https://api.weather.gov/alerts/urn:oid:2.49.0.1.840.0.a68fcf9bedf21fe106903c65ccf2638ca407a494.001.1",
                "@type": "wx:Alert",
                "event": "Heat Advisory",
                "severity": "Moderate",
                "headline": "Heat Advisory issued March 12 at 1:22PM PDT until March 13 at 8:00PM PDT by NWS Los Angeles/Oxnard CA",
                "description": "* WHAT...Widespread temperatures of 90 to 100 expected.\n\n* WHERE...A portion of southwest California.\n\n* WHEN...Until 8 PM PDT Friday.\n\n* IMPACTS...There is a high risk for heat illness for sensitive populations...",
                "instruction": "Drink plenty of fluids, stay in an air-conditioned room, stay out of the sun, and check up on relatives and neighbors."
            }
        }
    ]
}
```