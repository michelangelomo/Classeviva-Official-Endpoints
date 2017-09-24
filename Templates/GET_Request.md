# Enter Resource Name

    GET **endpoint name**

## Description
Enter description of resource


***

## Required Header
* Z-Dev-ApiKey
* Z-Auth-Token
* ...

***

## Parameters
- **type** _(required)_ — *type* is an example parameter which is required:
- **active** _(required)_ — *active* is an example parameter which is *default:false*:

***

## Response
- **success** — Boolean value.

***

## Errors
None

***

## Example
**Request**

    https://web.spaggiari.eu/rest/v1/students/{studentId}/noticeboard

**Return** __shortened response__
``` json
{
	"items": [
		{
			"pubId": 799423,
			"pubDT": "2017-09-24T17:09:45+02:00",
			"readStatus": false,
			"evtCode": "CF",
			"cntId": 351708,
			"cntValidFrom": "2017-09-24",
			"cntValidTo": "2017-10-31",
			"cntValidInRange": true,
			"cntStatus": "active",
			"cntTitle": "VACCINI E SCUOLA: COSA FARE ",
			"cntCategory": "Scuola\/famiglia",
			"cntHasChanged": false,
			"cntHasAttach": true,
			"needJoin": false,
			"needReply": false,
			"needFile": false
		},
		{
			"pubId": 796212,
			"pubDT": "2017-09-24T15:49:59+02:00",
			"readStatus": false,
			"evtCode": "CF",
			"cntId": 351672,
			"cntValidFrom": "2017-09-24",
			"cntValidTo": "2017-09-30",
			"cntValidInRange": true,
			"cntStatus": "active",
			"cntTitle": "VARIAZIONE ORARIO PROVVISORIO - LIEVI MODIFICHE",
			"cntCategory": "Scuola\/famiglia",
			"cntHasChanged": false,
			"cntHasAttach": true,
			"needJoin": false,
			"needReply": false,
			"needFile": false
		},
	]
}
```
