# 📘 Reference

The Arcadius API is a RESTful API that returns JSON responses. The API is available at the following base URL:

```URL
https://arcadius-azure.vercel.app
```

#### Error Codes

Arcadius API uses standard HTTP status codes to indicate the success or failure of an API request. Here are the possible HTTP status codes and their meanings:

| Status Code | Description                                                                          |
| ----------- | ------------------------------------------------------------------------------------ |
| 200         | OK. The request was successful.                                                      |
| 400         | Bad Request. The request was malformed or invalid.                                   |
| 401         | Unauthorized. The API key provided was invalid.                                      |
| 403         | Forbidden. The request was authenticated but does not have the necessary permission. |
| 404         | Not Found. The requested resource was not found.                                     |
| 500         | Internal Server Error. Something went wrong on the server side.                      |

#### Authentication

The Arcadius API currently does not require any API key or authentication to use the endpoints.

#### Versioning

The Arcadius API currently does not have any versioning in place.

