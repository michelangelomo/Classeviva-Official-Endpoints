# Document check

    POST **rest/v1/students/{studentId}/documents/check/{hash}**

## Description
This endpoint checks the status of a certain documet

## Required Header
* Z-Dev-ApiKey
* Z-Auth-Token
* User-Agent: zorro/1.0
* Z-Auth-Token: token

## Parameters
- **studentId** _(required)_ — your student id obtained with the login
- **hash** _(required)_ — the hash code of the document

## Example
**Request**

    https://web.spaggiari.eu/rest/v1/students/{studentId}/documents/check/{hash}

**Return** __shortened response__
``` json
{
   "document":{
      "available":true
   }
}
```
