# Documents

    POST **rest/v1/students/{studentId}/documents**

## Description
Get a list of the student's documents, like school reports

## Required Header
* Z-Dev-ApiKey
* Z-Auth-Token
* User-Agent: zorro/1.0
* Z-Auth-Token: token

## Parameters
- **studentId** _(required)_ — your student id obtained with the login:


## Example
**Request**

    https://web.spaggiari.eu/rest/v1/students/{studentId}/documents

**Return** __shortened response__
``` json
{
   "documents":[
      {
         "hash":"ad6192418c134c453948d254739167f5",
         "desc":"Document title here"
      }
   ],
   "schoolReports":[
      {
         "desc":"Recuperi",
         "confirmLink":"https://web.spaggiari.eu/sol/app/default/pubblicazioni.php?a=RA-LETTURA&desc=Recuperi",
         "viewLink":"https://web.spaggiari.eu/sol/app/default/scrutinio_singolo_recuperi.php?quad=1"
      },
      {
         "desc":"Pagella (Web) Primo Periodo",
         "confirmLink":"https://web.spaggiari.eu/sol/app/default/pubblicazioni.php?a=RA-LETTURA&desc=Pagella+%28Web%29+Primo+Periodo&sessione=S1",
         "viewLink":"https://web.spaggiari.eu/sol/app/default/genitori_singolo.php?quad=1"
      }
   ]
}
```
