# Deposit

A [Submission](Submission.md) that is deposited to a specific repository

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| status* | String: _new_, _in-progress_, or _accepted_  | Status of deposit |
| repository* 	| String | Repository being deposited to |
| assignedId | [Identifier](Identifier.md) | ID assigned by repository |
| requested | Boolean | True if deposit was requested by user rather than required by a policy |
| grant | [Grant](Grant.md) | Grant associated with deposit |
| updatedDate* | DateTime | Date the record was last updated |

*required
