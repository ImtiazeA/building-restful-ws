### Building a RESTful Web Service with Spring Boot 3.1.0 and Java 17

This project will build a service that will accept HTTP GET requests at `http://localhost:8080/greeting`.

It will respond with a JSON representation of a greeting, as the following listing shows:

```json
{
  "id": 1,
  "content": "Hello, World!"
}
```

To customize the greeting with an optional name parameter in the query string, as the following listing shows:

```http
http://localhost:8080/greeting?name=User
```

The name parameter value overrides the default value of `World` and is reflected in the response, as the following listing shows:

```json
{
  "id": 1,
  "content": "Hello, User!"
}
```

---

The project was developed following [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/ "Building a RESTful Web Service")
from  [Spring Guides](https://spring.io/guides "Spring Guides")
