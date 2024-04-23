# Get list of Certificates

### URL

/api/certificates/

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
        "id": 76617,
        "name": "Märkätilojen vedeneristäjäkoulutus",
        "name_en": "Wetroom installation card",
        "name_fi": "Märkätilojen vedeneristäjäkoulutus",
        "industry": null
    },
    {
        "id": 65370,
        "name": "Katto- ja vedeneristystöiden tulityökoulutus",
        "name_en": "Roofing and waterproofing card",
        "name_fi": "Katto- ja vedeneristystöiden tulityökoulutus",
        "industry": null
    }
]
```
