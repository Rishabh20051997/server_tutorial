# server_tutorial


# JWT Token
1. User Token & Refresh Token
2. Logout API, Refresh Token API
3. dot.env introduced.
4. Cookies used to send refresh token


# Steps to generate ACCESS_TOKEN_SECRET  & REFRESH_TOKEN_SECRET
Run this command in node -> require('crypto').randomBytes(64).toString('hex')
Note -> crypto is by default available

# Never post .env & other secret on github. This is dummy project. Hence pushed

# Valid Links
1. http://localhost:3500/index - Index Page
2. http://localhost:3500/ - Index Page
3. POST - auth -> To Login
4. POST - register -> To Register
5. GET, POST, PUT, DELETE /employees
6. GET /employee/:id


# Need to Recheck -> Cookies not working with refresh & logout in thunder client
