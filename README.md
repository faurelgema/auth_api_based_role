## Implementation of role access for authorized


### Running Project

1. create Database `auth-example`
2. run `go run main`


### How to access API

1. Create as admin first at http://localhost:8080/api/register (name, role, email, password)
2. login with email and password
3. if it's correct, you will get token. so copy the token at the response and put on bearer token to access the API CRUD
4. Enjoy.

### Example POSTMAN
![Screenshot (1202)](https://user-images.githubusercontent.com/67195019/168120538-ed8a3938-6950-4714-8141-78f9f7cd16d9.png)

