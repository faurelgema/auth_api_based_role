## Implementation of role access for authorized


### Running Project

1. create Database `auth-example`
2. run `go run main`


### How to access API

1. Create as admin first at http://localhost:8080/api/register (name, role, email, password)
2. login with email and password
3. if it's correct, you will get token. so copy the token at the response and put on bearer token to access the API CRUD
4. Enjoy.

### Middleware Workflow 

