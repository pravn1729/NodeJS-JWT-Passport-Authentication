<h1>JSONWebToken(JWT) Architecture:</h1>

This Project uses the JWT Authentication. Below are the Rest Endpoints.

<h2>Steps to import the project:</h2>
<ul>
<li>Enter into the project NodeJSJWTAuth from commandline</li>
<li>Run <b>npm install</b> . Install node packages.</li>
<li>Run <b>node main.js</b></li>
</ul>

<h2>Rest Endpoints:</h2> (Use POSTMAN plugin or any RestClient to hit the Endpoints)

For instance consider <b>baseUrl = http://localhost:3000 </b><br/>
<b>1) baseUrl/api/register - post request</b><br/>

<b>headers: </b><br/>
Content-Type : application/x-www-form-urlencoded<br/>

add email and password in the body<br/>

<b>2) baseUrl/api/authenticate- post request</b><br/>
email and password<br/>
gets a token in response<br/>

<b>headers: </b><br/>
Content-Type : application/x-www-form-urlencoded

<b>3) baseUrl/api/dashboard - get request </b><br/>
<b>headers:</b><br/>
Authorization : <<token>> <-- place the response token got in step 2.