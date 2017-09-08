# JSON-success-response
My JSON API standard response that can be also your.

 param|type|description
 -|-|-
 success|boolean| true if ok, false if error
 code|number| server status code
 result|string, number, boolean, array, object| response result
 time|string| response time in ISO standard
 
 ### Example
```json
{
  "success": true,
  "code": 200,
  "message": "ok",
  "result": 123,
  "time": "2017-08-30T09:59:00.846Z"
}
```

### Author
Fabio Ricali

### License
MIT
