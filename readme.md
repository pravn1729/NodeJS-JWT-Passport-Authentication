<h1>JSONWebToken(JWT) Architecture:</h1>

This Project uses the JWT Authentication. Below are the Rest Endpoints.

<h2>Steps to import the project:</h2>
<li>
<ul>Enter into the project NodeJSJWTAuth from commandline</ul>
<ul>Run <b>npm install</b> . Install node packages.</ul>
<ul>Run <b>node main.js</b></ul>
</li>

<h2>Rest Endpoints:</h2> (Use POSTMAN plugin or any RestClient to hit the Endpoints)

For instance consider baseUrl = http://localhost:3000
<b>1) baseUrl/api/register - post request</b>

<b>headers: </b>
Content-Type : application/x-www-form-urlencoded

add email and password in the body

<b>2) baseUrl/api/authenticate- post request</b>
email and password
gets a token in response

<b>headers: </b>
Content-Type : application/x-www-form-urlencoded

<b>3) baseUrl/api/dashboard - get request </b>
<b>headers:</b>
Authorization : <<token>> <-- place the response token got in step 2.