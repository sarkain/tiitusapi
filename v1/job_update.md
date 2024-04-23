# Update Job

*Update existing company job*

### URL

/api/external_job_api/[job_id]/

### Method

PATCH
  
### Request Headers

- Authorization: <my_token> [string]
    example "jwt eyJhbGciOiJIUzI1NiIsInR5cCI6Ik"

### Url Params

#### Required

- job_id: [integer]

### Data Params

#### Required

- application_deadline: [datetime_iso_string]
- character: {enums.jobs.character} [integer]
- city: [string]
  *this or coordinates is required*
- coordinates: [GeoPoint]
   *this or city is required*
   
   ```
   /* example */
   {type: "Point", coordinates: [60.169887, 24.938471]}
   ```
- duration: {enums.jobs.duration} [integer]
- employment_contract: {enums.jobs.employment_contract} [integer]
- job_starts: {enums.jobs.job_starts} [integer]
- published_date: [datetime_iso_string]
- salary: {enums.jobs.salary} [integer]
- title: [string]
- working_hours: {enums.jobs.working_hours} [integer]

#### Optional

- application_type: [integer]
  *Application type, (1) normal or (2) "fast"
- business_location: {BusinessLocation().id} [integer]
- certificates: {Certificate()} [list of objects]
  *Bulk save certificates*
  ```
  ref. certificates_get.md
  /* example */
  [{certificate:{id:9169,name:"ADR card"}}]
  ```
  
  (name is optional, added here for readability)

- competence: {enums.jobs.competence} [integer]
- competence_industry: {SchoolIndustry().id} [integer]
- country: [string]
- customer: {Customer().id} [integer]
  *aka Brand*
- count: [integer]
  *How many positions open, default=1*
- contact_person: {MyUser().id} [integer]
- description: [string]
- header_media: [binary]
- hobby_skills: {HobbySkillLevel()} [list of objects]
  *Bulk save hobby skills*
  ```
  ref. hobby_skills_get.md
  /* example */
  [{skill:{id:2931,name:"HR processes",industry:6},level:4}]
  ```
  
  (name is optional, added here for readability)
- is_external_job: [boolean]
  *Job is aplied in external website, ref. url_external*
- job_type: {enums.jobs.job_type} [integer]
- job_skills: {JobSkillLevel()} [list of objects]
  *Bulk save job skills*
  ```
  ref. job_skills_get.md
  /* example */
  [{skill:{id:8631,name:"Assistentti",industry:6},level:1}]
  ```
  
  (name is optional, added here for readability)
- job_starts_custom: [string]
  *Additional details when/where job starts etc.*
- language_skills: {LanguageSkillLevel()} [list of objects]
  *Bulk save language skills*
  ```
  ref. language_skills_get.md
  /* example */
  [{skill:{id:88262,name:"Finnish"},level:3}]
  ```
  
  (name is optional, added here for readability)
- postal_code: [string]
- payment_salary_custom: [string]
  *Custom salary payment text for employers*
- salary_custom_text: [string]
  *Custom salary text, used when salary choice is 8*
- street_address: [string]
- url_external: {link to external application} [string]
  *ref. is_external_job*


### Success Response

**Code:** 200 OK
  
**Content:**

```
{"id":12345}
```

### Error Response


### Notes
