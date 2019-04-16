# Document read

    POST **rest/v1/students/{studentId}/documents/read/{hash}**

## Description
This endpoint returns the raw binary content of a document

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

    https://web.spaggiari.eu/rest/v1/students/{studentId}/documents/read/{hash}

**Return**
```%PDF-1.4
%����
3 0 obj
<</Type /Page
/Parent 1 0 R
/MediaBox [0 0 595.280 841.890]
/TrimBox [0.000 0.000 595.280 841.890]
/Resources 2 0 R
/Group << /Type /Group /S /Transparency /CS /DeviceRGB >> 
/Contents 4 0 R>>
endobj
4 0 obj
<</Filter /FlateDecode /Length 1264>>
stream[...]
