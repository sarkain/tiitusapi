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

- character: {JOB_CHARACTERS} [integer]

- company: {Company().id} [integer]  
- duration: {WORK_DURATION} [integer]
- employment_contract: {EMPLOYMENT_CONTRACT} [integer]
- job_starts: {JOB_STARTS} [integer]
- salary: {SALARIES} [integer]
- title: [string]
- working_hours: {WORKING_HOURS} [list of integers]

#### Optional, but required before job is published

- city: [string]
  *this or coordinates is required*
- coordinates: [GeoPoint]
   *this or city is required*
   
   ```
   /* example */
   {type: "Point", coordinates: [60.169887, 24.938471]}
   ```

- published_date: 
   
- regions_sectors : {RegionsSector.id} [list of objects]
  *In which regions sectors job is published to*
  
  ```
   /* example */
   [{id: 1}, {id:2}]
   ```

#### Optional

- application_type: [integer]
  *Application type, (1) normal or (2) "fast"
- business_location: {BusinessLocation().id} [integer]
- certificates: {ValidatedCertificate()} [list of objects]
  *Bulk save certificates*
  ```
  ref. certificates_get.md
  /* example */
  [{certificate:{id:9169,name:"ADR card"}}]
  ```
  
  (name is optional, added here for readability)

- competence: {DEGREE_LEVEL} [integer]
- competence_industry: {SchoolIndustry} [integer]
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
- job_type: {JOB_TYPES} [integer]
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
- payment_type: {PAYMENT_TYPE} [integer]
- payment_salary_custom: [string]
  *Custom salary payment text for employers*
- salary_custom_text: [string]
  *Custom salary text, used when salary choice is 8*
- street_address: [string]
- url_external: {link to external application} [string]
  *ref. is_external_job*


### Success Response

**Code:** 201 Created
  
**Content:**

```
{"id":12345}
```

### Error Response


### Notes
