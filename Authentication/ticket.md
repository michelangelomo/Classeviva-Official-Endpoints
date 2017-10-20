# Ticket

    GET **v1/auth/ticket**

## Description
Sincerly, I don't know the utility

## Required Header
* Content-Type: application/json
* Z-Dev-ApiKey: +zorro+
* User-Agent: zorro/1.0
* Z-Auth-Token: *token*

## Parameters
none

## Example
**Request**

    https://web.spaggiari.eu/rest/v1/auth/ticket

**Return** __shortened response__
``` json
{
	"ticket": "*a string of 114 character*",
	"len": 108,
	"ulen": 114,
	"md5": "*a md5 string*"
}
```
