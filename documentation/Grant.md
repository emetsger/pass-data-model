# Grant

Grants/awards are received by one or more [Persons](Person.md) and can have 0 or more related [Submissions](Submission.md)

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| awardNumber* | String | Award number from funder |
| externalId 	| [Identifier](Identifier.md) | Award number or ID assigned to the grant within the researcher's institution e.g. from COEUS |
| projectName* | String | Title of the research project |
| funder* | [Funder](Funder.md) | Sponsor of grant |
| pi* | [Person](Person.md) | Principal investigator |
| coPis | List[[Person](Person.md)] | Co-principal investigator list |
| startDate | DateTime | Date the grant started |
| endDate | DateTime | Date the grant ended |
| alternateIds | List[Identifier] | Other identifiers _need examples, do we need these?_ |
| oapCompliance | Boolean | true if compliant, false if not compliant |
| submissions | List[[Submission](Submission.md)] | Submissions related to Grant |
| creator* | [User](User.md) | User who created record in PASS |
| creationDate* | DateTime | Date the record was created |

*required
