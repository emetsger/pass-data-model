# User

A user of the PASS system

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| id* | String | Unique User ID |
| username* | String | Unique login name used by user |
| usergroups* | List[String] | User's group for assignment to departmental groups. _Need more complex? could be one instead of list?_|	
| role* | String | User role |
| person* | [Person](Person.md) | Person associated with the account |
| creationDate* | DateTime | Date the record was created |
| updatedDate* | DateTime | Date the record was last updated |

*required
