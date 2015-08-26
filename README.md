# [Rep The House](jasonng.nyc)

Take a look at the site live [here](jasonng.nyc)

**Rep The House** is a political web application. Its purpose is to provide it's users easier access to information on the current legislators in the United States House of Representatives. The current APIs allow us to filter through information with regards to the current bills legislators are sponsoring, and the donations they have received. 

This web application is a single page app that which makes AJAX requests to two two seperate APIs using an Express.js server. I used vanilla JavaScript to manipulate the JSON data from the API calls, then used EJS templating to render the information. The bubble chart is being created using D3.js. The styling was done with CSS and Bootstrap. 

Want to give it a shot? Let's clone the repo

```
git clone https://github.com/Jingo88/RepTheHouse.git
```
* I gitignored a few files
* The first is my node_modules so make sure to install the dependencies from my package.json.

```
npm install
```
* The other two files I ignored from pushing to Git are two text files I used to hold my API keys. 
* I used the `fs` npm package to pull in these files and use them in my server.js
* Make sure to get your own API keys if you want to run this project. 
* My file names are

```
sunlightKey.txt
openKey.txt
```
* Great now lets go into the server file and change the port our server is listening to to port 3000 and run our server from the terminal

```
node server.js
```
* Last step, visit your `localhost:3000` and enjoy this plethora of knowledge!

### What Technologies Was Used To Build This?

* JavaScript 
* Node.js
* D3.js
* Express.js
* CSS
* Bootstrap CSS
* HTML
