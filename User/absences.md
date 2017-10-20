# Status

    GET **v1/students/{studentId}/absences/details[/{begin}/{end}]**

## Description
This endpoint provide the list of the absences

## Required Header
* Content-Type: application/json
* Z-Dev-ApiKey: +zorro+
* User-Agent: zorro/1.0
* Z-Auth-Token: *token*

## Parameters
* studentId: your student id obtained with the login
* begin: begin date in *yyyymmdd* (optional)
* end: end date in *yyyymmdd* (optional)

## Example
**Request**

    https://web.spaggiari.eu/rest/v1/students/{studentId}/absences/details

**Return** __shortened response__
``` json
{
	"events": [
		{
			"evtId": *int_number*,
			"evtCode": "string",
			"evtDate": "2017-09-20",
			"evtHPos": null,
			"evtValue": null,
			"isJustified": true,
			"justifReasonCode": "",
			"justifReasonDesc": "Ritardo Breve"
		},
		{
			"evtId": *int_number*,
			"evtCode": "string",
			"evtDate": "2017-10-20",
			"evtHPos": 1,
			"evtValue": 1,
			"isJustified": true,
			"justifReasonCode": "C",
			"justifReasonDesc": "Altri motivi"
		}
	]
}
```
