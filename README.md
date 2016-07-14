# norwegian-municipalities-json
JSON of Norwegian municipalities.

### Disclaimer

The data are parsed from [Wikipedia](https://no.wikipedia.org/wiki/Norges_kommuner) and may not be up to date.

Last update: 2016-05-19.

## Normal version
Contains municipality and county.

Example:
```json
[
  {
    "county": "Oslo",
    "municipalities": [
      "Oslo"
    ]
  }
]
```

## Detailed version
Contains number, municipality, county, population, area, language form, mayor and political party.

Example:
```json
[
  {
    "county": "Oslo",
    "municipalities": [
      {
        "number": "0301",
        "population": "647676",
        "area": "45403",
        "languageForm": "Nøytral",
        "mayor": "Marianne Borgen",
        "politicalParty": "SV",
        "name": "Oslo"
      }
    ]
  }
]
```
