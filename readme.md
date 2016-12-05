JsonWebToken Architecture:

This project contains the jwt authentication. below are the endpoints

1)api/register - post request

headers: 
Content-Type : application/x-www-form-urlencoded

add email and password in the body

2)api/authenticate- post request
email and password
gets a token in response

headers: 
Content-Type : application/x-www-form-urlencoded

3)api/dashboard - get request
headers --> Authorization : token