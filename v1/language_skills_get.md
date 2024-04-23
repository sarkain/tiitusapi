# Get list of Language Skills

### URL

/api/language_skills/

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
        "id": 53646,
        "name": "Suomi",
        "name_en": "Finnish",
        "name_fi": "Suomi",
        "weight": 1,
        "language_code": "fi"
    },
    {
        "id": 76825,
        "name": "Ruotsi",
        "name_en": "Swedish",
        "name_fi": "Ruotsi",
        "weight": 2,
        "language_code": "sv"
    },
]
```
