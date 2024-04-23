# Get list of Job Skills

### URL

/api/job_skills/

### Method

GET

### Success Response

**Code:** 200 OK
  
**Content:**

```
HTTP 200 OK
Allow: GET, POST, HEAD, OPTIONS
Content-Type: application/json
Vary: Accept

[
    {
        "id": 101088,
        "name": "Deaconess",
        "name_en": "Deaconess",
        "name_fi": "Diakonissa",
        "industry": 37
    },
    {
        "id": 101103,
        "name": "Hevostenhoitaja",
        "name_en": "Hevostenhoitaja",
        "name_fi": "Hevostenhoitaja",
        "industry": 18
    }
]
```
