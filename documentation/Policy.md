# Policy

A policy determines what rules should be followed by a [Submission](Submission.md).

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| id* | String | Unique policy ID |
| type* | String: _university_, _funder_ | Type of policy - whether implemented by funder, or the institution hosting PASS _Note: this is still a bit squishy, but could be used for logic to create a default repo_|
| title* | String | Title of policy e.g. "NIH Public Access Policy" |
| description | String | Several sentence description of policy |
| repositories* | List[[Repository](Repository.md)] | List of repositories that can satisfying this policy |
| creationDate* | DateTime | Date the record was created |
| updatedDate* | DateTime | Date the record was last updated |

*required

_Note: eventaully materialType could be added to this to support data etc._
