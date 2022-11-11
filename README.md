# Website-to-spot-fun-places
One need to create a .env file in the root of the project and add the following:
MAPBOX_TOKEN=<>
CLOUDINARY_CLOUD_NAME=<>
CLOUDINARY_SECRET=<>
CLOUDINARY_KEY=<>
For the above information one need to :
Create a cloudinary account to get an API key, secret code and cloud name.
Create an account on mapbox to get mapbox token
Run npm install on the terminal to install all the dependencies required .
Open mongod in one shell and mongo in another.
Run db.user.find({}) in mongo shell and copy user id of any one user whom you want
to be the owner of all funplaces in database and paste it in seeds/index.js in place of
author user ID.
Run nodemon app.js in the terminal with the project Then go to localhost:3000
