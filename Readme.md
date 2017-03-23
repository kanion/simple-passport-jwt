## How to use it?

1. Login
send json by POST method with
Content-Type application/json header
{
	"email": "john@mail.com",
	"password": "john123"
}

to http://localhost:3000/token

2. Copy token from response
3. Send GET to http://localhost:3000/user

Content-Type application/json header
Authorization JWT {pastedtoken}

replace {pastedtoken} by your token from step 1