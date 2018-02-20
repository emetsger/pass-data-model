# Person
A person who has either a [Grant](Grant.md) or a [Submission](Submission.md) associated with them.

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| id* | String | Unique person ID |
| firstName | String | First name(s) of person |
| middleName | String | Middle name(s) of person |
| lastName | String | Last name(s) of person |
| displayName* | String | Name for display. Separate names may not be available, but a person should always at least have a display name. |
| email* | String | Contact email for person |
| institutionalId | String | ID assigned by person's institution |
| orcidId | String | ORCID ID for the person |
| affiliation | String | Institution name |
| creationDate* | DateTime | Date the record was created |
| updatedDate* | DateTime | Date the record was last updated |

*required