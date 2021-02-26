create a directory called heroku-demo (You are NOT creating a new react app)
copy demo repo. 21-mern/05-Stu_ReactRouter/Solved into the heroku-demo
install stuff
npm install
install dotenv
create .env file => add .env to .gitignore
create mongo atlas db (see instructions for Atlas)
edit your URI and keep it handy:  mongodb+srv://<your url>
create heroku app
add MONGO_URI env variables to heroku: mongodb+srv://<your url>
In the app’s, .env file, add MONGO_URI=<add your production url> to .env
Add to server file:  require(‘dotenv’).config()
Comment out your mongo connection string in  /scripts/seedDB.js. Comment out the seeds.
commit to GitHub
In terminal add Heroku remote git URL - git remote add heroku <url here>
Push to GitHub: git push origin main
Push to Heroku: git push heroku main
