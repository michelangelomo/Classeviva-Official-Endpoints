# Classeviva Official Endpoints
This repository provide the list of official Endpoints for Classeviva

***

## Libraries
* Coming soon 👻

## How to contribute
If you want to contribute, please open a pull request using template file
***

## Endpoints
_API Url: <code>https://web.spaggiari.eu/rest/</code>_

## Request Header
- User-Agent: <code>zorro/1.0</code>
- Z-Dev-Apikey: <code>+zorro+</code>

_Warning: without these headers, the request will fail._

### Authentication
- **[<code>POST</code> v1/auth/login]()**
- **[<code>GET</code> v1/auth/avatar]()**
- **[<code>GET</code> v1/auth/status]()**
- **[<code>GET</code> v1/auth/ticket]()**

### User
##### Absence
- **[<code>GET</code> v1/students/_{studentId}_/absences/details]()**
- **[<code>GET</code> v1/students/_{studentId}_/absences/details/_{begin}_]()**
- **[<code>GET</code> v1/students/_{studentId}_/absences/details/_{begin}_/_{end}_]()**
##### Agenda
- **[<code>GET</code> v1/students/_{studentId}_/agenda/all/_{begin}_/_{end}_]()**
- **[<code>GET</code> v1/students/_{studentId}_/agenda/_{eventCode}_/_{begin}_/_{end}_]()**
##### Didactics
- **[<code>GET</code> v1/students/_{studentId}_/didactics]()**
- **[<code>GET</code> v1/students/_{studentId}_/didactics/item/_{contentId}_]()**
##### Notice Board
- **[<code>GET</code> v1/students/_{studentId}_/noticeboard]()**
- **[<code>GET</code> v1/students/_{studentId}_/noticeboard/read/_{eventCode}_/_{pubId}_/101]()**
- **[<code>GET</code> v1/students/_{studentId}_/noticeboard/attach/_{eventCode}_/_{pubId}_/101]()**
##### Schoolbooks
- **[<code>GET</code> v1/students/_{studentId}_/schoolbooks]()**
##### Calendar
- **[<code>GET</code> v1/students/_{studentId}_/calendar/all]()** 🤔🤔🤔
##### Card
- **[<code>GET</code> v1/students/_{studentId}_/card]()**
- **[<code>GET</code> v1/students/_{studentId}_/cards]()**
##### Grades
- **[<code>GET</code> v1/students/_{studentId}_/grades]()**
- **[<code>GET</code> v1/students/_{studentId}_/grades/subject/_{subject}_]()**
##### Lessons
- **[<code>GET</code> v1/students/_{studentId}_/lessons/today]()**
- **[<code>GET</code> v1/students/_{studentId}_/lessons/_{day}_]()**
- **[<code>GET</code> v1/students/_{studentId}_/lessons/_{start}_/_{end}_]()**
##### Notes
- **[<code>GET</code> v1/students/_{studentId}_/notes/all]()**
- **[<code>GET</code> v1/students/_{studentId}_/notes/type/_{type}_/read/_{note}_]()**
##### Periods
- **[<code>GET</code> v1/students/_{studentId}_/periods]()**
##### Subjects
- **[<code>GET</code> v1/students/_{studentId}_/subjects]()**

### QR-Code
##### Upload
- **[<code>POST</code> tools/app/default/app_qrcode_token.php?a=aUPLIMG]()**
