# [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice)

This is a simple javascript fullstack app which returns user ip-address, browser preferred language and browser software details in json format using headers.

## User Stories
> 1. A request to /api/whoami should return a JSON object with your IP address in the ipaddress key.
> 2. A request to /api/whoami should return a JSON object with your preferred language in the language key.
> 3. A request to /api/whoami should return a JSON object with your software in the software key.

## Example Usage
`[base url]/api/whoami`

## Example Output
```
{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5",
"software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}
```