<div>
<h1>JSON Success Response</h1>
My JSON API standard response that can be also your.
<br/><br/>
<img src="https://img.shields.io/badge/JSON-Success%20Response-green.svg" title="JSON Success Response"/> <a href="https://opensource.org/licenses/MIT" target="_blank"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" title="License: MIT"/></a>
</div>
<br/><br/>

 Param|Type|Description
 -|-|-
 success|boolean| true if ok, false if error
 code|number| server status code
 result|string, number, boolean, array, object, null| response result
 time|string| response time in ISO standard

 ### Example
 #### Response ok
```
HTTP/1.1 200 OK
Content-Type: application/json
```
```json
{
  "success": true,
  "code": 200,
  "message": "ok",
  "result": 123,
  "time": "2017-08-30T09:59:00.846Z"
}
```
 #### Response error
```
HTTP/1.1 401 Unauthorized
Content-Type: application/json
```
```json
{
  "success": false,
  "code": 401,
  "message": "Unauthorized",
  "result": null,
  "time": "2017-08-30T09:59:00.846Z"
}
```

### Author
Fabio Ricali

### License
MIT
