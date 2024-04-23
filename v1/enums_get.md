# Get enums/constants
  
*Get tiitus API enums/constants*

### URL

/api/enums/

### Method

GET
  
### URL Params

**Required:**

None

**Optional:**

- app_name: <app_name> [string]
*Lists the apps enums*

### Success Response

**Code:** 200 Ok
  
**Content:**

```
{
    "admin": {
        "log_entry": {
            "action_flag": [
                {
                    "value": "Lisäys",
                    "key": 1
                },
                {
                    "value": "Muokkaa",
                    "key": 2
                },
                {
                    "value": "Poisto",
                    "key": 3
                }
            ]
        }
    },
    "otp_totp": {
        "totp_device": {
            "digits": [
                {
                    "value": 6,
                    "key": 6
                },
                {
                    "value": 8,
                    "key": 8
                }
            ]
        }
    },
    "otp_hotp": {
        "hotp_device": {
            "digits": [
                {
                    "value": 6,
                    "key": 6
                },
                {
                    "value": 8,
                    "key": 8
                }
            ]
        }
    },
    "users": {
        "my_user": {
            "account_type": [
                {
                    "value": "Tiitus",
                    "key": 1
                },
                {
                    "value": "Facebook",
                    "key": 2
                },
                {
                    "value": "Turku",
                    "key": 3
                },
                {
                    "value": "Lahti",
                    "key": 4
                }
            ],
            "gender": [
                {
                    "value": "Mies",
                    "key": 1
                },
                {
                    "value": "Nainen",
                    "key": 2
                },
                {
                    "value": "Ei määritelty",
                    "key": 3
                }
            ],
            "account_status": [
                {
                    "value": "Aktivoitu",
                    "key": 1
                },
                {
                    "value": "Ei aktivoitu",
                    "key": 2
                }
            ],
            "match_calculation_status": [
                {
                    "value": "Ei aloitettu",
                    "key": 0
                },
                {
                    "value": "Lasketaan..",
                    "key": 1
                },
                {
                    "value": "Laskettu",
                    "key": 2
                }
            ],
            "account_origin": [
                {
                    "value": "Tiitus",
                    "key": 1
                },
                {
                    "value": "Facebook",
                    "key": 2
                },
                {
                    "value": "Turku",
                    "key": 3
                },
                {
                    "value": "Lahti",
                    "key": 4
                }
            ]
        }
    },
    "customers": {
        "customer": {
            "employee_count": [
                {
                    "value": "1-10",
                    "key": 1
                },
                {
                    "value": "10-100",
                    "key": 2
                },
                {
                    "value": "100-1000",
                    "key": 3
                },
                {
                    "value": "Yli 1000",
                    "key": 4
                }
            ],
            "company_type": [
                {
                    "value": "Tiitus",
                    "key": 1
                },
                {
                    "value": "Mol",
                    "key": 2
                },
                {
                    "value": "Turku",
                    "key": 3
                },
                {
                    "value": "Lahti",
                    "key": 4
                }
            ]
        }
    },
    "companies": {
        "company": {
            "employee_count": [
                {
                    "value": "1-10",
                    "key": 1
                },
                {
                    "value": "10-100",
                    "key": 2
                },
                {
                    "value": "100-1000",
                    "key": 3
                },
                {
                    "value": "Yli 1000",
                    "key": 4
                }
            ],
            "company_type": [
                {
                    "value": "Tiitus",
                    "key": 1
                },
                {
                    "value": "Mol",
                    "key": 2
                },
                {
                    "value": "Turku",
                    "key": 3
                },
                {
                    "value": "Lahti",
                    "key": 4
                }
            ],
            "subscription_class": [
                {
                    "value": "Määrittelemätön",
                    "key": 0
                },
                {
                    "value": "Starter",
                    "key": 1
                },
                {
                    "value": "Premium",
                    "key": 2
                },
                {
                    "value": "Pro",
                    "key": 3
                },
                {
                    "value": "Organisaatio",
                    "key": 4
                }
            ],
            "billing_type": [
                {
                    "value": "Sähköposti",
                    "key": 1
                },
                {
                    "value": "E-Lasku",
                    "key": 2
                }
            ]
        },
        "company_user_role": {
            "status": [
                {
                    "value": "Peruskäyttäjä",
                    "key": 10
                },
                {
                    "value": "Admin",
                    "key": 100
                }
            ]
        }
    },
    "jobs": {
        "job": {
            "job_type": [
                {
                    "value": "Tiitus",
                    "key": 1
                },
                {
                    "value": "MOL",
                    "key": 2
                },
                {
                    "value": "Turku",
                    "key": 3
                },
                {
                    "value": "Lahti",
                    "key": 4
                },
                {
                    "value": "organisaatio",
                    "key": 5
                }
            ],
            "duration": [
                {
                    "value": "1-10 päivää",
                    "key": 1
                },
                {
                    "value": "Alle 3 kuukautta",
                    "key": 2
                },
                {
                    "value": "Alle 6 kuukautta",
                    "key": 3
                },
                {
                    "value": "Alle 12 kuukautta",
                    "key": 4
                },
                {
                    "value": "Enemmän kuin 12 kuukautta",
                    "key": 5
                }
            ],
            "employment_contract": [
                {
                    "value": "Määräaikainen",
                    "key": 1
                },
                {
                    "value": "Toistaiseksi voimassaoleva",
                    "key": 2
                },
                {
                    "value": "Urakka",
                    "key": 3
                }
            ],
            "job_starts": [
                {
                    "value": "Heti",
                    "key": 1
                },
                {
                    "value": "Sopimuksen mukaan",
                    "key": 2
                },
                {
                    "value": "Vapaa teksti",
                    "key": 3
                }
            ],
            "salary": [
                {
                    "value": "TES",
                    "key": 1
                },
                {
                    "value": "Sopimuksen mukaan",
                    "key": 2
                },
                {
                    "value": "Urakkapalkka",
                    "key": 3
                },
                {
                    "value": "Harjottelijan palkka",
                    "key": 4
                },
                {
                    "value": "Provisio",
                    "key": 5
                },
                {
                    "value": "Provisio+peruspalkka",
                    "key": 6
                },
                {
                    "value": "Muu/palkaton",
                    "key": 7
                },
                {
                    "value": "Vapaa teksti",
                    "key": 8
                }
            ],
            "working_hours": [
                {
                    "value": "Kokopäivätyö",
                    "key": 1
                },
                {
                    "value": "Osa-aikatyö",
                    "key": 2
                }
            ],
            "character": [
                {
                    "value": "Työpaikka",
                    "key": 1
                },
                {
                    "value": "Oppisopimus",
                    "key": 3
                },
                {
                    "value": "Työharjoittelu",
                    "key": 4
                },
                {
                    "value": "Opinnäytetyö",
                    "key": 7
                }
            ],
            "competence": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Lukio",
                    "key": 1
                },
                {
                    "value": "Ammatillinen oppilaitos",
                    "key": 2
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 3
                },
                {
                    "value": "Yliopisto",
                    "key": 4
                },
                {
                    "value": "Opistoaste",
                    "key": 5
                },
                {
                    "value": "Muu",
                    "key": 6
                }
            ],
            "lahti_job_pathway": [
                {
                    "value": "Kokeilupolku",
                    "key": 1
                },
                {
                    "value": "Oppipolku",
                    "key": 2
                },
                {
                    "value": "Työpolku",
                    "key": 3
                },
                {
                    "value": "Yrittäjyyspolku",
                    "key": 4
                }
            ],
            "mol_job_character": [
                {
                    "value": "Työnantaja",
                    "key": 1
                },
                {
                    "value": "Vuokratyö",
                    "key": 2
                },
                {
                    "value": "Työnvälitys",
                    "key": 3
                }
            ],
            "application_type": [
                {
                    "value": "Normaali",
                    "key": 1
                },
                {
                    "value": "Nopea",
                    "key": 2
                }
            ],
            "mol_category": [
                {
                    "value": "Sotilaat: upseerit, aliupseerit ja sotilasammattihenkilöstö",
                    "key": 0
                },
                {
                    "value": "Johtajat: ylimmät virkamiehet, hallintojohtajat, kaupalliset johtajat, tuotantotoiminnan ja yhteiskunnan peruspalvelujen johtajat, hotelli- ja ravintola-alan, vähittäiskaupan ja muiden palvelualojen johtajat",
                    "key": 1
                },
                {
                    "value": "Erityisasiantuntijat: luonnontieteet ja tekniikka, terveydenhuolto, opettajat ja muu opetusala, liike-elämä ja hallinto, tieto- ja viestintäteknologia, lainopillinen, sosiaaliala ja kulttuuriala",
                    "key": 2
                },
                {
                    "value": "Asiantuntijat: luonnontieteet ja tekniikka, terveydenhuolto, liike-elämä ja hallinto, lainopilliset avustajat sekä sosiaali- ja kulttuuriala, informaatio- tietoliikenneteknologia",
                    "key": 3
                },
                {
                    "value": "Toimisto- ja asiakaspalvelutyöntekijät: toimistotyöntekijät, asiakaspalvelutyöntekijät, laskennan ja varastoinnin toimistotyöntekijät, muut toimisto- ja asiakaspalvelutyöntekijät",
                    "key": 4
                },
                {
                    "value": "Palvelu- ja myyntityöntekijät: palvelutyöntekijät, myyjät, kauppiaat, hoivapalvelun ja terveydenhuollon työntekijät, suojelu- ja vartiointityöntekijät",
                    "key": 5
                },
                {
                    "value": "Maanviljelijät, metsätyöntekijät: maanviljelijät ja eläintenkasvattajat, metsä- ja kalatalouden työntekijät",
                    "key": 6
                },
                {
                    "value": "Rakennus-, korjaus- ja valmistustyöntekijät: rakennustyöntekijät, konepaja- ja valimotyöntekijät sekä asentajat ja korjaajat, käsityötuotteiden valmistajat, hienomekaanikot sekä painoalan työntekijät, sähkö- ja elektronikka-alan työtekijät, elintarvike- puutyö- ja vaatetus- ja jalkinealan valmistustyöntekijät",
                    "key": 7
                },
                {
                    "value": "Prosessi- ja kuljetustyöntekijät: prosessityöntekijät, teollisuustuotteiden kokoonpanijat, kuljetustyöntekijät",
                    "key": 8
                },
                {
                    "value": "Muut työntekijät: Siiivojat, kotiapulaiset ja muut puhdistustyöntekijät, maa-, metsä- ja kalatalouden avustavat työntekijät, teollisuuden ja rakentamisen avustavat työntekijät, avustavat keittiö- ja ruokatyöntekijät, katumyyjät, katujen puhtaanapidon ja jätehuollon työntekijät",
                    "key": 9
                }
            ]
        }
    },
    "skills": {
        "job_skill_level": {
            "level": [
                {
                    "value": "Perustaidot",
                    "key": 1
                },
                {
                    "value": "Keskitasoa",
                    "key": 2
                },
                {
                    "value": "Kokenut",
                    "key": 3
                },
                {
                    "value": "Asiantuntija",
                    "key": 4
                }
            ]
        },
        "language_skill_level": {
            "level": [
                {
                    "value": "Perustaidot",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Kiitettävä",
                    "key": 4
                },
                {
                    "value": "Erinomainen",
                    "key": 5
                }
            ]
        },
        "hobby_skill_level": {
            "level": [
                {
                    "value": "Perustaidot",
                    "key": 1
                },
                {
                    "value": "Keskitasoa",
                    "key": 2
                },
                {
                    "value": "Kokenut",
                    "key": 3
                },
                {
                    "value": "Asiantuntija",
                    "key": 4
                }
            ]
        },
        "hobby": [
            {
                "value": "Käsityö",
                "key": 9
            },
            {
                "value": "Musiikki",
                "key": 7
            },
            {
                "value": "Ruoanlaitto",
                "key": 8
            },
            {
                "value": "Taide",
                "key": 6
            },
            {
                "value": "Ulkoilu",
                "key": 4
            },
            {
                "value": "Urheilu",
                "key": 5
            },
            {
                "value": "Muu",
                "key": 3
            }
        ],
        "allergy": [
            {
                "value": "Ruoka-aine",
                "key": 2
            },
            {
                "value": "Lääkeaine",
                "key": 3
            },
            {
                "value": "Eläin",
                "key": 4
            },
            {
                "value": "Kemikaali",
                "key": 5
            },
            {
                "value": "Muu",
                "key": 6
            }
        ],
        "computer_skill": [
            {
                "value": "Excel",
                "key": 2
            },
            {
                "value": "Office",
                "key": 1
            },
            {
                "value": "Mikä muu: ?",
                "key": 3
            }
        ]
    },
    "installations": {
        "installation": {
            "device_os": [
                {
                    "value": "iOS",
                    "key": 1
                },
                {
                    "value": "Android",
                    "key": 2
                }
            ]
        }
    },
    "applications": {
        "application": {
            "status": [
                {
                    "value": "Aktiivinen",
                    "key": 1
                },
                {
                    "value": "Passiivinen",
                    "key": 2
                },
                {
                    "value": "Valittu",
                    "key": 3
                },
                {
                    "value": "Ei valittu",
                    "key": 5
                },
                {
                    "value": "Valittu haastatteluun",
                    "key": 6
                },
                {
                    "value": "Kontaktoitu",
                    "key": 8
                }
            ]
        },
        "open_application": {
            "status": [
                {
                    "value": "Aktiivinen",
                    "key": 1
                },
                {
                    "value": "Passiivinen",
                    "key": 2
                },
                {
                    "value": "Valittu",
                    "key": 3
                },
                {
                    "value": "Ei valittu",
                    "key": 5
                },
                {
                    "value": "Valittu haastatteluun",
                    "key": 6
                },
                {
                    "value": "Kontaktoitu",
                    "key": 8
                }
            ]
        },
        "history": {
            "status": [
                {
                    "value": "Lähetetty",
                    "key": 1
                },
                {
                    "value": "Prosessissa",
                    "key": 2
                },
                {
                    "value": "CV avattu",
                    "key": 3
                },
                {
                    "value": "Valittu",
                    "key": 4
                },
                {
                    "value": "Ei valittu",
                    "key": 5
                }
            ]
        },
        "open_application_history": {
            "status": [
                {
                    "value": "Lähetetty",
                    "key": 1
                },
                {
                    "value": "Read",
                    "key": 2
                }
            ]
        }
    },
    "experiences": {
        "education_experience": {
            "competence": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Lukio",
                    "key": 1
                },
                {
                    "value": "Ammatillinen oppilaitos",
                    "key": 2
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 3
                },
                {
                    "value": "Yliopisto",
                    "key": 4
                },
                {
                    "value": "Opistoaste",
                    "key": 5
                },
                {
                    "value": "Muu",
                    "key": 6
                }
            ]
        }
    },
    "schools": {
        "degree_programme": {
            "level": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Lukio",
                    "key": 1
                },
                {
                    "value": "Ammatillinen oppilaitos",
                    "key": 2
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 3
                },
                {
                    "value": "Yliopisto",
                    "key": 4
                },
                {
                    "value": "Opistoaste",
                    "key": 5
                },
                {
                    "value": "Muu",
                    "key": 6
                }
            ]
        }
    },
    "media": {
        "media": {
            "media_type": [
                {
                    "value": "Kuva",
                    "key": 1
                },
                {
                    "value": "Plink",
                    "key": 2
                },
                {
                    "value": "Video",
                    "key": 3
                },
                {
                    "value": "Tiedosto",
                    "key": 4
                }
            ],
            "tags": [],
            "industries": [
                {
                    "value": "Laki ja oikeus",
                    "key": 1
                },
                {
                    "value": "Turvallisuus, suojelu ja valvonta",
                    "key": 2
                },
                {
                    "value": "Julkishallinto, yhteiskunta ja järjestöt",
                    "key": 3
                },
                {
                    "value": "Markkinointi ja viestintä",
                    "key": 4
                },
                {
                    "value": "Yrittäjyys ja johtajuus",
                    "key": 5
                },
                {
                    "value": "Hallinto, talous ja henkilöstö",
                    "key": 6
                },
                {
                    "value": "Arkkitehtuuri ja suunnittelu",
                    "key": 7
                },
                {
                    "value": "Rakennusala, huolto ja asennus",
                    "key": 8
                },
                {
                    "value": "Hotelli- ravintola- ja matkailuala",
                    "key": 9
                },
                {
                    "value": "IT ja Ohjelmistojen kehitys",
                    "key": 10
                },
                {
                    "value": "Koulutus ja konsultointi",
                    "key": 11
                },
                {
                    "value": "Liikenne, kuljetus ja logistiikka",
                    "key": 12
                },
                {
                    "value": "Myynti ja asiakaspalvelu",
                    "key": 13
                },
                {
                    "value": "Pankki-, rahoitus- ja vakuutusala",
                    "key": 14
                },
                {
                    "value": "Tekniikka ja teollisuus",
                    "key": 15
                },
                {
                    "value": "Sosiaali- ja terveysala",
                    "key": 16
                },
                {
                    "value": "Kirjoitus, kielet ja tulkkaus",
                    "key": 17
                },
                {
                    "value": "Luonnontieteet ja maa- ja metsätalous",
                    "key": 18
                },
                {
                    "value": "Lääketeollisuus ja farmasia",
                    "key": 19
                },
                {
                    "value": "Tutkimus ja kehittämistoiminta",
                    "key": 20
                },
                {
                    "value": "Kiinteistöala ja puhtaanapito",
                    "key": 21
                },
                {
                    "value": "Musiikki, kulttuuri ja humanistinen ala",
                    "key": 22
                },
                {
                    "value": "Elintarvikeala",
                    "key": 23
                },
                {
                    "value": "Ympäristö ja kierrätys",
                    "key": 27
                },
                {
                    "value": "Ostotoiminta",
                    "key": 29
                },
                {
                    "value": "Kauneus, liikunta ja hyvinvointia",
                    "key": 39
                },
                {
                    "value": "Ravitsemusala",
                    "key": 41
                }
            ]
        },
        "applicants_media": {
            "media_type": [
                {
                    "value": "Kuva",
                    "key": 1
                },
                {
                    "value": "Plink",
                    "key": 2
                },
                {
                    "value": "Video",
                    "key": 3
                },
                {
                    "value": "Tiedosto",
                    "key": 4
                }
            ]
        }
    },
    "news": {
        "news": {
            "category": [
                {
                    "value": "Mobiilivinkit",
                    "key": 1
                },
                {
                    "value": "Hallintapaneelin uutiset",
                    "key": 2
                },
                {
                    "value": "Tiitus Students uutiset",
                    "key": 3
                },
                {
                    "value": "TET uutiset",
                    "key": 4
                }
            ]
        }
    },
    "notes": {
        "note": {
            "applicant_status": [
                {
                    "value": "Etsii kokoaikatyötä",
                    "key": 1
                },
                {
                    "value": "Etsii osa-aikatyötä",
                    "key": 2
                },
                {
                    "value": "Hiljainen työnhakija",
                    "key": 3
                },
                {
                    "value": "Passiivinen",
                    "key": 4
                },
                {
                    "value": "Työssä (meillä)",
                    "key": 5
                }
            ]
        }
    },
    "all_users": {
        "all_users_filter": {
            "competence": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Lukio",
                    "key": 1
                },
                {
                    "value": "Ammatillinen oppilaitos",
                    "key": 2
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 3
                },
                {
                    "value": "Yliopisto",
                    "key": 4
                },
                {
                    "value": "Opistoaste",
                    "key": 5
                },
                {
                    "value": "Muu",
                    "key": 6
                }
            ]
        }
    },
    "academies": {
        "academy": {
            "css_class": [
                {
                    "value": "default",
                    "key": ""
                },
                {
                    "value": "tet",
                    "key": "tet"
                }
            ],
            "academy_type": [
                {
                    "value": "AMK",
                    "key": 0
                },
                {
                    "value": "Ammatillinen koulutus",
                    "key": 1
                },
                {
                    "value": "Lukio",
                    "key": 2
                }
            ],
            "identifier": [
                {
                    "value": "oletus",
                    "key": 0
                },
                {
                    "value": "hyria",
                    "key": 1
                },
                {
                    "value": "turku",
                    "key": 2
                },
                {
                    "value": "lahti",
                    "key": 4
                }
            ],
            "type": [
                {
                    "value": "oppilaitos",
                    "key": 0
                },
                {
                    "value": "organisaatio",
                    "key": 1
                }
            ],
            "company_license_status_default": [
                {
                    "value": "Hyväksytty",
                    "key": 1
                },
                {
                    "value": "Kieltäytynyt",
                    "key": 2
                },
                {
                    "value": "Odottaa",
                    "key": 3
                }
            ],
            "billing_type": [
                {
                    "value": "Sähköposti",
                    "key": 1
                },
                {
                    "value": "E-Lasku",
                    "key": 2
                }
            ]
        },
        "student_group_user": {
            "year_class": [
                {
                    "value": "syksy",
                    "key": 1
                },
                {
                    "value": "kevät",
                    "key": 2
                }
            ]
        },
        "academy_user_role": {
            "status": [
                {
                    "value": "peruskäyttäjä",
                    "key": 1
                },
                {
                    "value": "organisaatio-käyttäjä",
                    "key": 10
                },
                {
                    "value": "organisaatio-admin",
                    "key": 100
                }
            ]
        },
        "academy_user_role_invitation": {
            "invitation_status": [
                {
                    "value": "Luotu",
                    "key": 0
                },
                {
                    "value": "Lähetetty",
                    "key": 1
                },
                {
                    "value": "Hyväksytty",
                    "key": 2
                },
                {
                    "value": "Kieltäytynyt",
                    "key": 3
                }
            ],
            "status": [
                {
                    "value": "peruskäyttäjä",
                    "key": 1
                },
                {
                    "value": "organisaatio-käyttäjä",
                    "key": 10
                },
                {
                    "value": "organisaatio-admin",
                    "key": 100
                }
            ]
        },
        "academy_company_group": {
            "status": [
                {
                    "value": "Hyväksytty",
                    "key": 1
                },
                {
                    "value": "Kieltäytynyt",
                    "key": 2
                },
                {
                    "value": "Odottaa",
                    "key": 3
                }
            ]
        },
        "academy_public_tag": {
            "type": [
                {
                    "value": "Lukio",
                    "key": 0
                },
                {
                    "value": "Ammatillinen koulutus",
                    "key": 1
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 2
                },
                {
                    "value": "Yliopisto",
                    "key": 3
                },
                {
                    "value": "Opistoaste",
                    "key": 4
                },
                {
                    "value": "Muu koulutus",
                    "key": 5
                }
            ]
        }
    },
    "mol_api": {
        "mol_jobs_model": {
            "mol_flag": [
                {
                    "value": "UUSI",
                    "key": 1
                },
                {
                    "value": "LISÄTTY TYÖPAIKKOIHIN",
                    "key": 2
                },
                {
                    "value": "HYLÄTTY",
                    "key": 3
                }
            ]
        }
    },
    "educations": {
        "education": {
            "education_type": [
                {
                    "value": "työvoimakoulutus",
                    "key": 1
                },
                {
                    "value": "rekrykoulutus",
                    "key": 2
                },
                {
                    "value": "tutkintoon johtava koulutus",
                    "key": 3
                },
                {
                    "value": "täydennyskoulutus",
                    "key": 4
                },
                {
                    "value": "korttikoulutus",
                    "key": 5
                },
                {
                    "value": "muu koulutus",
                    "key": 6
                },
                {
                    "value": "henkilöstökoulutus",
                    "key": 7
                },
                {
                    "value": "muu koulutus",
                    "key": 99
                }
            ],
            "education_form": [
                {
                    "value": "päivä",
                    "key": 1
                },
                {
                    "value": "ilta",
                    "key": 2
                },
                {
                    "value": "etä",
                    "key": 3
                },
                {
                    "value": "monimuoto",
                    "key": 4
                }
            ],
            "target_group": [
                {
                    "value": "Kaikki",
                    "key": 0
                },
                {
                    "value": "Opiskelijat",
                    "key": 1
                },
                {
                    "value": "Työnantajat",
                    "key": 2
                }
            ]
        }
    },
    "analytics": {
        "stats": {
            "workspace": [
                {
                    "value": "default",
                    "key": 0
                },
                {
                    "value": "tiitus",
                    "key": 1
                },
                {
                    "value": "tiitus (7 days)",
                    "key": 2
                }
            ]
        },
        "stats_row": {
            "workspace": [
                {
                    "value": "default",
                    "key": 0
                },
                {
                    "value": "tiitus",
                    "key": 1
                },
                {
                    "value": "tiitus (7 days)",
                    "key": 2
                }
            ]
        }
    },
    "regions": {
        "regions_sector": {
            "identifier": [
                {
                    "value": "0:None",
                    "key": 0
                },
                {
                    "value": "1:tiitus",
                    "key": 1
                },
                {
                    "value": "3:tyovoimahautomot",
                    "key": 3
                },
                {
                    "value": "4:lahti",
                    "key": 4
                },
                {
                    "value": "5:Business college Rekry",
                    "key": 5
                },
                {
                    "value": "7:SampoRekry",
                    "key": 7
                },
                {
                    "value": "8:MercuriaWORKS",
                    "key": 8
                },
                {
                    "value": "9:Metropolia",
                    "key": 9
                },
                {
                    "value": "10:Haaga-Helia",
                    "key": 10
                },
                {
                    "value": "12:Duuni GradiaPoke",
                    "key": 12
                },
                {
                    "value": "13:Lamk duuni",
                    "key": 13
                },
                {
                    "value": "14:HyriaRekry",
                    "key": 14
                },
                {
                    "value": "15:RiveriaRekry",
                    "key": 15
                },
                {
                    "value": "16:Kiertotalousrekry",
                    "key": 16
                },
                {
                    "value": "18:Edupoli",
                    "key": 18
                },
                {
                    "value": "19:Suomen Diakoniaopisto",
                    "key": 19
                },
                {
                    "value": "20:Citywork",
                    "key": 20
                },
                {
                    "value": "21:Rakennusliitto",
                    "key": 21
                },
                {
                    "value": "22:HR-yhtiöt",
                    "key": 22
                },
                {
                    "value": "23:Projektivoima",
                    "key": 23
                },
                {
                    "value": "24:Citysote",
                    "key": 24
                },
                {
                    "value": "1002:MOL",
                    "key": 1002
                },
                {
                    "value": "1003:Profiili",
                    "key": 1003
                },
                {
                    "value": "1030:Demokoulu",
                    "key": 1030
                },
                {
                    "value": "1031:Sarkain koulutus",
                    "key": 1031
                },
                {
                    "value": "2001:tiitus starter",
                    "key": 2001
                },
                {
                    "value": "2002:tiitus haavi",
                    "key": 2002
                },
                {
                    "value": "2003:tiitus pro",
                    "key": 2003
                },
                {
                    "value": "3001:tiitus market place",
                    "key": 3001
                },
                {
                    "value": "3002:frank market place",
                    "key": 3002
                },
                {
                    "value": "4001:TET",
                    "key": 4001
                }
            ],
            "landing_page": [
                {
                    "value": "tiitus intro",
                    "key": 0
                },
                {
                    "value": "market",
                    "key": 1
                }
            ],
            "color_theme": [
                {
                    "value": "oppilaitos",
                    "key": "marketAcademy"
                },
                {
                    "value": "sininen",
                    "key": "marketBlue"
                },
                {
                    "value": "frank",
                    "key": "marketFrank"
                },
                {
                    "value": "vihreä",
                    "key": "marketGreen"
                },
                {
                    "value": "tetti",
                    "key": "marketTet"
                },
                {
                    "value": "tiitus",
                    "key": "marketTiitus"
                },
                {
                    "value": "turku",
                    "key": "marketTurku"
                },
                {
                    "value": "rakennusliitto",
                    "key": "marketRakennusliitto"
                },
                {
                    "value": "matkalladuuniin",
                    "key": "marketLahti"
                }
            ]
        },
        "regions_sector_license": {
            "identifier": [
                {
                    "value": "0:None",
                    "key": 0
                },
                {
                    "value": "1:tiitus",
                    "key": 1
                },
                {
                    "value": "3:tyovoimahautomot",
                    "key": 3
                },
                {
                    "value": "4:lahti",
                    "key": 4
                },
                {
                    "value": "5:Business college Rekry",
                    "key": 5
                },
                {
                    "value": "7:SampoRekry",
                    "key": 7
                },
                {
                    "value": "8:MercuriaWORKS",
                    "key": 8
                },
                {
                    "value": "9:Metropolia",
                    "key": 9
                },
                {
                    "value": "10:Haaga-Helia",
                    "key": 10
                },
                {
                    "value": "12:Duuni GradiaPoke",
                    "key": 12
                },
                {
                    "value": "13:Lamk duuni",
                    "key": 13
                },
                {
                    "value": "14:HyriaRekry",
                    "key": 14
                },
                {
                    "value": "15:RiveriaRekry",
                    "key": 15
                },
                {
                    "value": "16:Kiertotalousrekry",
                    "key": 16
                },
                {
                    "value": "18:Edupoli",
                    "key": 18
                },
                {
                    "value": "19:Suomen Diakoniaopisto",
                    "key": 19
                },
                {
                    "value": "20:Citywork",
                    "key": 20
                },
                {
                    "value": "21:Rakennusliitto",
                    "key": 21
                },
                {
                    "value": "22:HR-yhtiöt",
                    "key": 22
                },
                {
                    "value": "23:Projektivoima",
                    "key": 23
                },
                {
                    "value": "24:Citysote",
                    "key": 24
                },
                {
                    "value": "1002:MOL",
                    "key": 1002
                },
                {
                    "value": "1003:Profiili",
                    "key": 1003
                },
                {
                    "value": "1030:Demokoulu",
                    "key": 1030
                },
                {
                    "value": "1031:Sarkain koulutus",
                    "key": 1031
                },
                {
                    "value": "2001:tiitus starter",
                    "key": 2001
                },
                {
                    "value": "2002:tiitus haavi",
                    "key": 2002
                },
                {
                    "value": "2003:tiitus pro",
                    "key": 2003
                },
                {
                    "value": "3001:tiitus market place",
                    "key": 3001
                },
                {
                    "value": "3002:frank market place",
                    "key": 3002
                },
                {
                    "value": "4001:TET",
                    "key": 4001
                }
            ]
        }
    },
    "projects": {
        "project": {
            "project_starts": [
                {
                    "value": "heti",
                    "key": 1
                },
                {
                    "value": "sopimuksen mukaan",
                    "key": 2
                }
            ],
            "duration": [
                {
                    "value": "1-10 päivää",
                    "key": 1
                },
                {
                    "value": "Alle 3 kuukautta",
                    "key": 2
                },
                {
                    "value": "Alle 6 kuukautta",
                    "key": 3
                },
                {
                    "value": "Alle 12 kuukautta",
                    "key": 4
                },
                {
                    "value": "Enemmän kuin 12 kuukautta",
                    "key": 5
                }
            ],
            "charge": [
                {
                    "value": "ilmainen",
                    "key": 1
                },
                {
                    "value": "sopimuksen mukaan",
                    "key": 2
                }
            ],
            "competence": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Lukio",
                    "key": 1
                },
                {
                    "value": "Ammatillinen oppilaitos",
                    "key": 2
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 3
                },
                {
                    "value": "Yliopisto",
                    "key": 4
                },
                {
                    "value": "Opistoaste",
                    "key": 5
                },
                {
                    "value": "Muu",
                    "key": 6
                }
            ],
            "target_group": [
                {
                    "value": "Kaikki",
                    "key": 0
                },
                {
                    "value": "Opiskelijat",
                    "key": 1
                },
                {
                    "value": "Työnantajat",
                    "key": 2
                },
                {
                    "value": "Kevytyrittäjät",
                    "key": 3
                }
            ]
        }
    },
    "educational_institutions": {
        "educational_institution": {
            "billing_type": [
                {
                    "value": "Sähköposti",
                    "key": 1
                },
                {
                    "value": "E-Lasku",
                    "key": 2
                }
            ]
        },
        "educational_institution_user_role": {
            "role": [
                {
                    "value": "koulun jäsen",
                    "key": 1
                },
                {
                    "value": "opinto-ohjaaja",
                    "key": 10
                },
                {
                    "value": "koulun ylläpitäjä",
                    "key": 100
                }
            ]
        },
        "educational_institution_class_user_role": {
            "role": [
                {
                    "value": "oppilas",
                    "key": 1
                },
                {
                    "value": "opettaja",
                    "key": 10
                },
                {
                    "value": "ylläpitäjä",
                    "key": 100
                }
            ]
        }
    },
    "work_practice_program": {
        "work_practice_program_period": {
            "type": [
                {
                    "value": "3 päivää",
                    "key": 1
                },
                {
                    "value": "5 päivää",
                    "key": 2
                },
                {
                    "value": "7 päivää",
                    "key": 3
                },
                {
                    "value": "10 päivää",
                    "key": 4
                },
                {
                    "value": "12 päivää",
                    "key": 5
                },
                {
                    "value": "14 päivää",
                    "key": 6
                }
            ]
        },
        "work_practice_program_agreement": {
            "type": [
                {
                    "value": "3 päivää",
                    "key": 1
                },
                {
                    "value": "5 päivää",
                    "key": 2
                },
                {
                    "value": "7 päivää",
                    "key": 3
                },
                {
                    "value": "10 päivää",
                    "key": 4
                },
                {
                    "value": "12 päivää",
                    "key": 5
                },
                {
                    "value": "14 päivää",
                    "key": 6
                }
            ],
            "status": [
                {
                    "value": "odottaa vastausta kutsuun",
                    "key": 0
                },
                {
                    "value": "luotu",
                    "key": 1
                },
                {
                    "value": "odottaa",
                    "key": 2
                },
                {
                    "value": "hyväksytty",
                    "key": 3
                },
                {
                    "value": "suoritettu",
                    "key": 4
                },
                {
                    "value": "arkistoitu",
                    "key": 5
                }
            ],
            "transportation_type": [
                {
                    "value": "Oma kyyti",
                    "key": 1
                },
                {
                    "value": "Bussi",
                    "key": 2
                },
                {
                    "value": "Muu",
                    "key": 3
                }
            ],
            "eating_type": [
                {
                    "value": "Koulu",
                    "key": 1
                },
                {
                    "value": "Työpaikka",
                    "key": 2
                },
                {
                    "value": "Maksettu ateria",
                    "key": 3
                },
                {
                    "value": "Eväät",
                    "key": 4
                }
            ]
        },
        "work_practice_program_agreement_note": {
            "motivation": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Tyydyttävä",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ]
        },
        "work_practice_program_agreement_signature": {
            "role": [
                {
                    "value": "Oppilas",
                    "key": 1
                },
                {
                    "value": "Työnantaja",
                    "key": 2
                },
                {
                    "value": "Koulu",
                    "key": 3
                },
                {
                    "value": "Huoltaja",
                    "key": 4
                }
            ]
        },
        "work_practice_program_review": {
            "behavior": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ],
            "accuracy": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ],
            "hard_working": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ],
            "self_initiative": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ]
        },
        "work_practice_program_student_review": {
            "overall_rating": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ],
            "industry_interest": [
                {
                    "value": "Heikko",
                    "key": 1
                },
                {
                    "value": "Kohtalainen",
                    "key": 2
                },
                {
                    "value": "Hyvä",
                    "key": 3
                },
                {
                    "value": "Erinomainen",
                    "key": 4
                }
            ]
        },
        "companies_invited_to_work_practice_program": {
            "status": [
                {
                    "value": "odottaa vastausta kutsuun",
                    "key": 0
                },
                {
                    "value": "luotu",
                    "key": 1
                },
                {
                    "value": "odottaa",
                    "key": 2
                },
                {
                    "value": "hyväksytty",
                    "key": 3
                },
                {
                    "value": "suoritettu",
                    "key": 4
                },
                {
                    "value": "arkistoitu",
                    "key": 5
                }
            ]
        }
    },
    "events": {
        "event": {
            "target_group": [
                {
                    "value": "Kaikki",
                    "key": 0
                },
                {
                    "value": "Opiskelijat",
                    "key": 1
                },
                {
                    "value": "Työnantajat",
                    "key": 2
                }
            ]
        }
    },
    "categories": {
        "category": {
            "category_type": [
                {
                    "value": "tapahtuma",
                    "key": 1
                }
            ]
        }
    },
    "geocoding": {
        "google_query": {
            "query_type": [
                {
                    "value": "oletus",
                    "key": 0
                },
                {
                    "value": "hae osoite",
                    "key": 1
                },
                {
                    "value": "hae koordinaatit",
                    "key": 2
                }
            ]
        }
    },
    "profile_bank": {
        "employment_status": {
            "state": [
                {
                    "value": "Töissä meillä",
                    "key": 0
                },
                {
                    "value": "Töissä muualla",
                    "key": 1
                }
            ]
        }
    },
    "applicants_watchers": {
        "applicants_watcher_profile": {
            "email_notification_recurrence": [
                {
                    "value": "Pois päältä",
                    "key": 0
                },
                {
                    "value": "Jokaisesta osumasta",
                    "key": 1
                },
                {
                    "value": "Kerran päivässä",
                    "key": 2
                },
                {
                    "value": "Kerran viikossa",
                    "key": 3
                },
                {
                    "value": "Kerran kuukaudessa",
                    "key": 4
                }
            ],
            "order_competence": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Lukio",
                    "key": 1
                },
                {
                    "value": "Ammatillinen oppilaitos",
                    "key": 2
                },
                {
                    "value": "Ammattikorkeakoulu",
                    "key": 3
                },
                {
                    "value": "Yliopisto",
                    "key": 4
                },
                {
                    "value": "Opistoaste",
                    "key": 5
                },
                {
                    "value": "Muu",
                    "key": 6
                }
            ],
            "order_duration": [
                {
                    "value": "1-10 päivää",
                    "key": 1
                },
                {
                    "value": "Alle 3 kuukautta",
                    "key": 2
                },
                {
                    "value": "Alle 6 kuukautta",
                    "key": 3
                },
                {
                    "value": "Alle 12 kuukautta",
                    "key": 4
                },
                {
                    "value": "Enemmän kuin 12 kuukautta",
                    "key": 5
                }
            ],
            "order_employment_contract": [
                {
                    "value": "Määräaikainen",
                    "key": 1
                },
                {
                    "value": "Toistaiseksi voimassaoleva",
                    "key": 2
                },
                {
                    "value": "Urakka",
                    "key": 3
                }
            ],
            "order_job_ends": [
                {
                    "value": "Heti",
                    "key": 1
                },
                {
                    "value": "Sopimuksen mukaan",
                    "key": 2
                },
                {
                    "value": "Vapaa teksti",
                    "key": 3
                }
            ],
            "order_job_starts": [
                {
                    "value": "Heti",
                    "key": 1
                },
                {
                    "value": "Sopimuksen mukaan",
                    "key": 2
                },
                {
                    "value": "Vapaa teksti",
                    "key": 3
                }
            ],
            "order_salary": [
                {
                    "value": "TES",
                    "key": 1
                },
                {
                    "value": "Sopimuksen mukaan",
                    "key": 2
                },
                {
                    "value": "Urakkapalkka",
                    "key": 3
                },
                {
                    "value": "Harjottelijan palkka",
                    "key": 4
                },
                {
                    "value": "Provisio",
                    "key": 5
                },
                {
                    "value": "Provisio+peruspalkka",
                    "key": 6
                },
                {
                    "value": "Muu/palkaton",
                    "key": 7
                },
                {
                    "value": "Vapaa teksti",
                    "key": 8
                }
            ]
        },
        "applicants_watcher_applicant": {
            "group": [
                {
                    "value": "Avoin",
                    "key": 1
                },
                {
                    "value": "Ehdotettu",
                    "key": 2
                },
                {
                    "value": "Poistettu",
                    "key": 3
                },
                {
                    "value": "Ohitettu",
                    "key": 4
                },
                {
                    "value": "Valittu",
                    "key": 5
                },
                {
                    "value": "Profiilipankki",
                    "key": 6
                },
                {
                    "value": "Haavi",
                    "key": 7
                },
                {
                    "value": "Työ",
                    "key": 8
                },
                {
                    "value": "Haastateltu",
                    "key": 9
                }
            ]
        },
        "applicants_watcher_task": {
            "status": [
                {
                    "value": "Odottaa",
                    "key": 1
                },
                {
                    "value": "Käynnissä",
                    "key": 2
                },
                {
                    "value": "Suoritettu",
                    "key": 3
                },
                {
                    "value": "Epäonnistui:Aikakatkaisu",
                    "key": 4
                },
                {
                    "value": "Epäonnistui:Virhe",
                    "key": 5
                }
            ]
        }
    },
    "sms_messages": {
        "sms_message_status": {
            "status": [
                {
                    "value": "CREATED",
                    "key": 1
                },
                {
                    "value": "SENT",
                    "key": 2
                },
                {
                    "value": "ACKED",
                    "key": 3
                },
                {
                    "value": "FAILED",
                    "key": 4
                },
                {
                    "value": "DELIVERED",
                    "key": 5
                },
                {
                    "value": "UNKNOWN",
                    "key": 6
                },
                {
                    "value": "RETRY",
                    "key": 7
                },
                {
                    "value": "TIITUS_ERROR",
                    "key": 8
                }
            ],
            "reason": [
                {
                    "value": "BUFFERED",
                    "key": 1
                },
                {
                    "value": "EXPIRED",
                    "key": 2
                },
                {
                    "value": "CANCELED",
                    "key": 3
                },
                {
                    "value": "FILTERED",
                    "key": 4
                },
                {
                    "value": "INVALID",
                    "key": 5
                },
                {
                    "value": "TERMINAL_ERROR",
                    "key": 6
                },
                {
                    "value": "CARRIER_ERROR",
                    "key": 7
                },
                {
                    "value": "BILLING_ERROR",
                    "key": 8
                },
                {
                    "value": "SEND_ERROR",
                    "key": 9
                },
                {
                    "value": "LIMIT_EXCEEDED",
                    "key": 10
                },
                {
                    "value": "SENDING_FAILED",
                    "key": 11
                }
            ]
        }
    },
    "request_token": {
        "request_token": {
            "login_mode": [
                {
                    "value": "Do not authenticate",
                    "key": "None"
                },
                {
                    "value": "Authenticate a single request",
                    "key": "Request"
                },
                {
                    "value": "Authenticate for the entire session",
                    "key": "Session"
                }
            ]
        }
    },
    "job_watcher": {
        "job_watcher_task": {
            "status": [
                {
                    "value": "Odottaa",
                    "key": 1
                },
                {
                    "value": "Käynnissä",
                    "key": 2
                },
                {
                    "value": "Suoritettu",
                    "key": 3
                },
                {
                    "value": "Epäonnistui:Aikakatkaisu",
                    "key": 4
                },
                {
                    "value": "Epäonnistui:Virhe",
                    "key": 5
                }
            ]
        }
    },
    "qualifications": {
        "qualification": {
            "type": [
                {
                    "value": "AMK",
                    "key": 0
                },
                {
                    "value": "Ammatillinen koulutus",
                    "key": 1
                },
                {
                    "value": "Lukio",
                    "key": 2
                }
            ],
            "level": [
                {
                    "value": "Ammatillinen perustutkinto",
                    "key": 0
                },
                {
                    "value": "Ammattitutkinto",
                    "key": 1
                },
                {
                    "value": "Erikoisammattitutkinto",
                    "key": 2
                },
                {
                    "value": "Muu tutkinto",
                    "key": 3
                }
            ]
        }
    },
    "admin_data": {
        "admin_param": {
            "type": [
                {
                    "value": "merkkijono",
                    "key": 0
                },
                {
                    "value": "kokonaisluku",
                    "key": 1
                },
                {
                    "value": "float",
                    "key": 2
                }
            ]
        },
        "email_template": {
            "email_template_type": [
                {
                    "value": "text",
                    "key": 0
                },
                {
                    "value": "text+html",
                    "key": 1
                }
            ]
        }
    },
    "training": {
        "training_period": {
            "state": [
                {
                    "value": "Luonnos",
                    "key": 1
                },
                {
                    "value": "Kutsu lähetetty",
                    "key": 2
                },
                {
                    "value": "Paikat vahvistettu",
                    "key": 3
                },
                {
                    "value": "Oppilaat vahvistettu",
                    "key": 4
                },
                {
                    "value": "Arkistoitu",
                    "key": 5
                },
                {
                    "value": "Cancelled",
                    "key": 6
                }
            ],
            "area": [
                {
                    "value": "Lappi",
                    "key": 1
                },
                {
                    "value": "Pohjois-Pohjanmaa",
                    "key": 2
                },
                {
                    "value": "Kainuu",
                    "key": 3
                },
                {
                    "value": "Pohjois-Karjala",
                    "key": 4
                },
                {
                    "value": "Pohjois-Savo",
                    "key": 5
                },
                {
                    "value": "Etelä-Savo",
                    "key": 6
                },
                {
                    "value": "Etelä-Karjala",
                    "key": 7
                },
                {
                    "value": "Keski-Suomi",
                    "key": 8
                },
                {
                    "value": "Etelä-Pohjanmaa",
                    "key": 9
                },
                {
                    "value": "Pohjanmaa",
                    "key": 10
                },
                {
                    "value": "Keski-Pohjanmaa",
                    "key": 11
                },
                {
                    "value": "Pirkanmaa",
                    "key": 12
                },
                {
                    "value": "Satakunta",
                    "key": 13
                },
                {
                    "value": "Päijät-Häme",
                    "key": 14
                },
                {
                    "value": "Kanta-Häme",
                    "key": 15
                },
                {
                    "value": "Kymenlaakso",
                    "key": 16
                },
                {
                    "value": "Uusimaa",
                    "key": 17
                },
                {
                    "value": "Lounais-Suomi",
                    "key": 18
                },
                {
                    "value": "Ahvenanmaa",
                    "key": 19
                }
            ]
        },
        "training_period_invite_response": {
            "state": [
                {
                    "value": "Avoin",
                    "key": 1
                },
                {
                    "value": "Hyväksy",
                    "key": 2
                },
                {
                    "value": "Kieltäydy",
                    "key": 3
                }
            ]
        },
        "confirmed_training_period_postions": {
            "state": [
                {
                    "value": "Varattu",
                    "key": 1
                },
                {
                    "value": "Vahvistettu",
                    "key": 2
                }
            ]
        },
        "confirmed_training_period_postions_student": {
            "state": [
                {
                    "value": "Varattu",
                    "key": 1
                },
                {
                    "value": "Vahvistettu",
                    "key": 2
                }
            ]
        }
    },
    "company_coins": {
        "coin_account_transaction": {
            "transaction_type": [
                {
                    "value": "Credit",
                    "key": 0
                },
                {
                    "value": "Debit",
                    "key": 1
                }
            ],
            "transaction_target": [
                {
                    "value": "Not specified / other",
                    "key": 0
                },
                {
                    "value": "Deposit",
                    "key": 1
                },
                {
                    "value": "Withdraw",
                    "key": 2
                },
                {
                    "value": "Deposit: Monthly pro add",
                    "key": 3
                },
                {
                    "value": "CoinBenefit",
                    "key": 4
                }
            ]
        },
        "coin_benefit": {
            "benefit_type": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Työ",
                    "key": 1
                }
            ],
            "benefit_code": [
                {
                    "value": "Ei mitään",
                    "key": 0
                },
                {
                    "value": "Job: Advertise in top jobs",
                    "key": 1
                },
                {
                    "value": "Job: Social media",
                    "key": 2
                },
                {
                    "value": "Job: Push",
                    "key": 3
                },
                {
                    "value": "Job: Newsletter",
                    "key": 4
                },
                {
                    "value": "Job: tiitus.fi",
                    "key": 5
                }
            ]
        }
    },
    "notifications": {
        "user_notification": {
            "object_type": [
                {
                    "value": "StudentGroupRegionSectorMessage",
                    "key": 1
                },
                {
                    "value": "Test",
                    "key": 2
                },
                {
                    "value": "StudentNewTrainingPeriodNotification",
                    "key": 3
                }
            ]
        }
    },
    "clean_manager": {
        "clean_log": {
            "log_type": [
                {
                    "value": "default / not defined",
                    "key": 0
                },
                {
                    "value": "delete archived users",
                    "key": 1
                }
            ],
            "log_status": [
                {
                    "value": "oletus",
                    "key": 0
                },
                {
                    "value": "onnistui",
                    "key": 1
                },
                {
                    "value": "failed",
                    "key": 2
                }
            ]
        }
    },
    "analytics_service": {
        "raw_data_queue": {
            "status": [
                {
                    "value": "avoin",
                    "key": 1
                },
                {
                    "value": "onnistui",
                    "key": 2
                },
                {
                    "value": "virhe",
                    "key": 3
                }
            ]
        }
    },
    "sendinblue_contacts": {
        "sendinblue_list": {
            "contacts_role": [
                {
                    "value": "Työnhakijakäyttäjä",
                    "key": 1
                },
                {
                    "value": "Yrityskäyttäjä",
                    "key": 2
                },
                {
                    "value": "Organisaatiokäyttäjä",
                    "key": 3
                }
            ]
        }
    },
    "auditlog": {
        "log_entry": {
            "action": [
                {
                    "value": "create",
                    "key": 0
                },
                {
                    "value": "update",
                    "key": 1
                },
                {
                    "value": "delete",
                    "key": 2
                },
                {
                    "value": "access",
                    "key": 3
                }
            ]
        }
    },
    "vismapay": {
        "visma_order": {
            "status": [
                {
                    "value": "Avoin",
                    "key": 2
                },
                {
                    "value": "Paid",
                    "key": 3
                }
            ]
        },
        "subscription": {
            "related_object_type": [
                {
                    "value": "Yritys",
                    "key": 2
                }
            ]
        }
    },
    "service_messages": {
        "service_message_task": {
            "status": [
                {
                    "value": "Odottaa",
                    "key": 1
                },
                {
                    "value": "In progress",
                    "key": 2
                },
                {
                    "value": "Failed",
                    "key": 3
                },
                {
                    "value": "Suoritettu",
                    "key": 4
                }
            ]
        }
    }
}
```

### Error Response


### Notes
