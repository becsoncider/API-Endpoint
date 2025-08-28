# API-Endpoint

README file instructions to successfully run the API endpoint code for Tongariro Cinemas. 

Open Terminal 

Run Commands: 
npm init -y
npm install express

Create a js file titled 'server' 
Run API code

Run Command:
node server.js

API will run on http://localhost:4000

Input link http://localhost:4000 into web browser to test if server is running

Open Postman 
Create new request

Method: Get
Input link http://localhost:4000/movies
Click send to receive movie titles

Method: Post
Input link http://localhost:4000/movies
Body -> raw -> JSON
Click send to add a movie

Method: Put
Input link http://localhost:4000/movies/1
Body -> raw -> JSON
Click send to update a movie

Method: Delete
Input link http://localhost:4000/movies/1 
Click send to delete a movie


