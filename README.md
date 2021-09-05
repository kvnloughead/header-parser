# [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice)

Deployed on heroku at https://parse-my-header.herokuapp.com/

## Usage

Requests to

```
https://parse-my-header.herokuapp.com/api/whoami
```

will return info about the client:

```
{ 
  ipaddress,  # x-forwarded-for header
  language,   # accept-language header
  software    # user-agent header
}
```
