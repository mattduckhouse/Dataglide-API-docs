# Related documents

The Dataglide API allows access to documents related to the instruments that the system holds. 
These documents might include KIID documents, prospectus and other fund produced documentation.

```[GET] /RelatedDocuments/ByIsin/{isin}```

Returns a list of documents related to the specified ISIN.

```
[
  {
    "relatedEntity": "ShareClasses",
    "relatedId": "<GUID>",
    "documentId": "<GUID>",
    "languages": [ "en" ],
    "publicationCountries": [ "FR", "DE" ],
    "documentType": "PR",
    "applicableDate": "2023-04-23",
    "createdOnDateTime": "2023-04-23T18:25:43.511Z",
    "sizeInBytes": "123",
    "contentHash": "ey2648jhhw22"
  },
  { ... }
]
```

