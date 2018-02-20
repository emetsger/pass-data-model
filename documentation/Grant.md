# Grant

Grants/awards are received by one or more [Persons](Person.md) and can have 0 or more related [Submissions](Submission.md)

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| id* 			| String 	| Unique grant identifier |
| awardNumber* | String | Award number from funder |
| localAwardId 	| String | Award number or ID assigned to the grant within the researcher's institution |
| projectName* | String | Title of the research project |
| primaryFunder* | [Funder](Funder.md) | Primary sponsor of grant |
| otherFunders | List[[Funder](Funder.md)] | Other sponsors of grant |
| pi* | [Person](Person.md) | Principal investigator |
| coPis | List[[Person](Person.md)] | Co-principal investigator list |
| awardDate* | DateTime | Date the grant was awarded |
| startDate | DateTime | Date the grant started |
| endDate | DateTime | Date the grant ended |
| oapCompliance | Boolean | true if compliant, false if not compliant |
| submissions | List[[Submission](Submission.md)] | Submissions related to Grant |
| creator* | [User](User.md) | User who created record in PASS |
| creationDate* | DateTime | Date the record was created |
| updatedDate* | DateTime | Date the record was last updated |

*required
