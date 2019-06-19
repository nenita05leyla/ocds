# Contract Date Created

## Description 
### Extension fields 
This extension adds `dateCreated` field to the` contracts` section of OCDS.
Describes creation date of a contract. If the data were published retrospectively this field
indicates the creation date of a contract to compare it with the `period` section to analize differences 
between inicial period of contract and the creation of itself.

## Example

The following JSON snippet models a `dateCreated` field:

```json
"contracts": [
	{
		"id": "3075-423-CL18",
		"awardID": "8385580",
		"title": "Contrato XXX",
		"description": "XXXX",
		"status": "active",
		"period": {
			"startDate": "2018-11-07T00:00:00Z",
			"endDate": "2019-12-31T00:00:00Z",
			"durationInDays": 419
		},		
		"dateCreated": "2018-11-12T12:22:53Z"
	}
]
```
