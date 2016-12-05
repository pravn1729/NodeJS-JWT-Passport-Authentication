<h1>JsonWebToken Architecture:</h1>

This project contains the jwt authentication. below are the endpoints

<b>1)api/register - post request</b>

<b>headers: </b>
Content-Type : application/x-www-form-urlencoded

add email and password in the body

<b>2)api/authenticate- post request</b>
email and password
gets a token in response

<b>headers: </b>
Content-Type : application/x-www-form-urlencoded

<b>3)api/dashboard - get request </b>
<b>headers:</b>
Authorization : token