# Journal

A [Submission](submission) may be a manuscript from a Journal. The journal may have an affect on the route of the submission.

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| id* | String | Unique repository ID |
| name* | String | Name of the journal |
| issn | List[String] | Journal ISSNs _note this was originally an "identifier" can it be a string list? do we need to know if it's an epub?_ |
| nlmta | String | _what is this?_ |
| pmcParticipation | String | For PubMed Central specifically, this determines the route for submission. |
| creationDate* | DateTime | Date the record was created |
| updatedDate* | DateTime | Date the record was last updated |

*required
