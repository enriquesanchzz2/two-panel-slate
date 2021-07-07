# API Reference Documentation Example
The following is an example of an API Resource and Endpoint reference documentation. 


# Projects
The Projects resource enables you to interact with the Project profiles in Watson.
The following table describes the available endpoints of the Projects resource:


| Endpoint | Description |
| -------- | ----------- |
| <a href="#get-projects" class="get-endpoint-word">GET</a> /projects | Retrieves the data objects of the Project profiles available in Watson. |
| <a href="#post-projects" class="post-endpoint-word">POST</a> /projects | Creates a new Project profile. |
| <a href="#put-projects-project" class="put-endpoint-word">PUT</a> /projects/{project} | Updates the data object of a Project profile. |
| <a href="#delete-projects-project" class="delete-endpoint-word">DELETE</a> /projects/{project} | Deletes a Project profile. |


## GET /PROJECTS
<p class="get-endpoint">GET</p>

### Summary
The **GET /PROJECTS** endpoint retrieves the data objects of the Project profiles available in Watson. 

### Parameters
This endpoint allows the following parameters:

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| from | Query | The Project identification number | No | Integer |
| size | Query | The number of Projects to retrieve. | No | Integer |

### Responses
This endpoint receives the following response code:

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### Sample Request
These are examples of an API request to this endpoint: 

#### cURL Request
`curl -X GET --header 'Accept: application/json' 'http://watson-api-nonprod.us-east-1.elasticbeanstalk.com/api/projects?from=0&size=2'`

#### HTTP Request
` http://watson-api-nonprod.us-east-1.elasticbeanstalk.com/api/projects?from=0&size=2 `



### Sample Response Body
The sample JSON file at the right of the page presents the Response Body obtained with the Sample Request.

```json
{
  "total": 27,
  "from": 0,
  "pageSize": 2,
  "results": [
    {
      "project": "Test-Project",
      "projectTeam": "Test Team",
      "projectBu": "Test BU",
      "projectRepository": "Test Repo",
      "lastActivity": 1623427403030,
      "timestamp": 1582927868192
    },
    {
      "project": "Allesseh.Ingest",
      "projectTeam": "Allesseh",
      "projectBu": "Allesseh",
      "projectRepository": "git@github.dowjones.net:Content/Allesseh.Ingest.git",
      "lastActivity": 1623349358757,
      "timestamp": 1622645743073
    }
  ]
}
```


### Sample Response Headers
The sample JSON file at the right of the page presents the Response Headers obtained with the Sample Request.

```json
{
  "access-control-allow-headers": "Content-Type, Last-Update",
  "access-control-allow-methods": "POST, GET, OPTIONS, PUT, DELETE",
  "access-control-allow-origin": "*",
  "cache-control": "no-cache, private, no-store",
  "connection": "keep-alive",
  "content-encoding": "gzip",
  "content-type": "application/json;charset=utf-8",
  "date": "Fri, 18 Jun 2021 03:49:02 GMT",
  "expires": "Fri, 18 Jun 2021 03:49:02 GMT",
  "pragma": "no-cache",
  "server": "nginx/1.18.0",
  "transfer-encoding": "chunked"
}
```