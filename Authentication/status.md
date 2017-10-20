# Status

    GET **v1/auth/status**

## Description
This endpoint provide the timestamp of the relase and expire date of the token, the remaining time in seconds and the user ID.

## Required Header
* Content-Type: application/json
* Z-Dev-ApiKey: +zorro+
* User-Agent: zorro/1.0
* Z-Auth-Token: *token*

## Parameters
none

## Example
**Request**

    https://web.spaggiari.eu/rest/v1/auth/status

**Return** __shortened response__
``` json
{
	"status": {
		"expire": "2017-10-20T13:14:23+02:00",
		"release": "2017-10-20T11:44:23+02:00",
		"ident": "*********",
		"remains": 5238
	}
}
```
