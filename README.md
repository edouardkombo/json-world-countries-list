# json-world-countries-list
This repository will give you a JSON list of all countries in the world, with their:
    - Translated names (in English, Spanish, Portuguese, Japanese and in native language) 
    - Respective country code
    - Language code(s).

I chose JSON format as it holds the most flexibility of use.

The format is as below below:
```
    {
        "country_name": {
            "en": "Singapore",
            "native": "Singapore",
            "es": "Singapur",
            "pt": "Singapura",
            "ja": "シンガポール"
        },
        "country_code": "SG",
        "language_code": [
            "en",
            "ms",
            "ta",
            "zh"
        ]
    }
```

Feel free to extend that list to your needs.

Enjoy!
