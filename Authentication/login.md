# Login

    POST **v1/auth/login**

## Description
Authentication on ClasseViva

## Required Header
* Content-Type: application/json
* Z-Dev-ApiKey: +zorro+
* User-Agent: zorro/1.0

## Body

    {"ident":null,"pass":"user_pass","uid":"user_id"}

## Example
**Request**

    https://web.spaggiari.eu/rest/v1/auth/login

**Response**
``` json
{
	"ident": "USER_ID",
	"firstName": "USER_FIRSTNAME",
	"lastName": "USER_LASTNAME",
	"token": "USER_TOKEN", //Needed for authentication
	"release": "2017-09-28T20:29:25+02:00",
	"expire": "2017-09-28T21:59:25+02:00"
}
```
