## Implementation of role access for authorized


### Running Project

1. create Database `auth-example`
2. run `go run main`


### How to access API

1. Create as admin first at http://localhost:8080/api/register (name, role, email, password)
2. login with email and password
3. if it's correct, you will get token. so copy the token at the response and put on bearer token to access the API CRUD
4. Enjoy.

### Flow of policy and rules of auth.
![casbin-middleware](https://user-images.githubusercontent.com/67195019/168121705-0352b0a5-9e2c-4082-8173-86b6c93fda47.jpg)
![casbin-workflow](https://user-images.githubusercontent.com/67195019/168121723-7679e903-683a-4743-ba67-b8c76443bbee.jpg)

### Example POSTMAN
1. create user/admin
![Screenshot (1202)](https://user-images.githubusercontent.com/67195019/168120538-ed8a3938-6950-4714-8141-78f9f7cd16d9.png)

2. login and get token
![Screenshot (1203)](https://user-images.githubusercontent.com/67195019/168120865-ef878f9f-cf9a-4da5-80f8-e4b4f7aa6f78.png)

3. use token for getAllUser
![Screenshot (1205)](https://user-images.githubusercontent.com/67195019/168121117-263ab5ce-b170-425c-9ce8-cf804da9014e.png)

the rest of api still undocumented
