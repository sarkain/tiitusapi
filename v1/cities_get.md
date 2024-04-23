# Get list of City objects

*Get list of cities from Tiitus city database, includes all Finland's cities*

### URL

/api/cities/cities/

### Method

GET

### Query Params

**Optional:**

- codes: [string] `"1,3,5"`
    *Filter City.code(s)*
- country_ids: [string] `"1,3,5"`
    *Filter City(s) by Country.id(s)*
- names: [string] `"Turku"`
    *Filter City.name, exact city name*
- province_ids: [string] `"1,3,5"`
    *Filter City(s) by Province.id(s)*
- starts_with: [string] `"Tur"`
    *Filter City.name, case-insensitive city name starts-with.*

### Success Response

**Code:** 200 OK
  
**Content:**

```
[
    {
        "id": 394,
        "code": 1,
        "name": "Aura",
        "coordinates": {
            "type": "Point",
            "coordinates": [
                60.6467431,
                22.59121719999996
            ]
        },
        "province": 1
    },
    {
        "id": 395,
        "code": 2,
        "name": "Kaarina",
        "coordinates": {
            "type": "Point",
            "coordinates": [
                60.4095118,
                22.38412649999998
            ]
        },
        "province": 1
    }
]
```

### Error Response


### Notes
