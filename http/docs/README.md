# aferox-http-restful-protocol

## Old Version

> Not available

## Version 1.0

### The relationship between RESTful API and file permissions

|method|permission|explain|
|---|---|---|
| GET    | R | OPEN / READ |
| PUT    | W | NEW / WRITE |
| DELETE | W | DELETE      |
| POST   | X | Run         |

### The relationship between code and error

|code|error|explain|
|---|---|---|
| 200 | nil            |  |
| 403 | no permission  |  |
| 404 | not found      |  |
| 500 | e.g. open fail |  |
