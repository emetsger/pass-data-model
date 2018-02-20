# Submission
Details of a submission that can be managed through PASS.

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| id* | String | Unique Submission ID |
| status* |  String: _need to define options_ | Status of Submission |
| title* | String | Title of work represented by Submission e.g. the title of the article |
| authors* | List[[Person](Person.md)]  | List of authors for work represented by Submission |
| abstract | String | Abstract for work represented by Submission |
| doi | String | DOI of item being submitted |
| copyright | String | Copyright status of item being submitted _is this just for info, or is it used?_  |
| journal | [Journal](Journal.md) | Journal the submission is part of (if article) |
| volume | String | Volume of journal that contains item (if article) |
| issue | String | Issue of journal that contains item (if article) |
| deposits | List[[Deposit](Deposit.md)] | List of places the submission will be deposited to |
| grants | List[[Grant](Grant.md)] | List of grants associated with the submission |
| workflows | List[[Workflow](Workflow.md)] | Workflows track the status of submission process |
| submittedDate | DateTime | Date the record was submitted |
| creator | [User](User.md) | PASS user that created submission |
| creationDate | DateTime | Date the record was created |
| updatedDate | DateTime | Date the record was last updated |

*required

_Note: could link policies directly here or calculate each time based on relevant properties_

## NIHMS Submission Fields

In addition to the fields above, NIHMS includes the following

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| tbd* |  String | tbd |

*required

## JScholarship Submission Fields

In addition to the fields above, JScholarship includes the following

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| tbd* |  String | tbd |

*required
