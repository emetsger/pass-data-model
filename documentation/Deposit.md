# Deposit

A [Submission](Submission.md) can have multiple Deposits, each to a different [Repository](Repository.md). This model describes a single deposit to a [Repository](Repository.md) and captures its current status.

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| __id*__ | String | Unique Deposit URI |
| status* | Enum ([_see list below_](#status-options)) | Status of deposit |
| repository* 	| [Repository](Repository.md) | Repository being deposited to |
| assignedId | String | ID assigned by repository |
| accessUrl | String | URL to access the item in the repository, could allow Users to see the final result |
| requested | Boolean | True if deposit was requested by user rather than required by a policy |
| createdBy*	| [User](User.md)|User who created record in PASS |
| __created*__ | DateTime | Date the record was created |
| __lastModified*__ | DateTime | Date the record was last modified |

*required  
_autogenerated fields are in **bold** and are readonly_

## Status options

These are the possible statuses for a Deposit

| Value  		| Description |
| ------------- | ------------- |
| prepared | Deposits that have been created, sitting in our system, waiting to be sent off |
| deposited | Deposits that have left the queue and sent off to their target repository |
| ... | _Others to be determined by use cases, possibly "received", "awaiting approval" etc._ |