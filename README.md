# Smart Brain

This app is able to recognize faces from given images. 
The front end is built entirely in React while the backend server is created using Express.js, and PostgreSQL is the database management system of choice.

# Usage
A user must sign in using their credentials or if they do not have an account they must register one.

Once registered, the user is able to access their main page, where they are able to enter an URL of an image containing faces.\
(NOTE! The URL entered must be the URL of the image address! If selecting a picture from Google, make sure that the URL being entered doesn't redirect to another website, otherwise the program will throw an error)

Once the URL is entered, the image will display below the input form and a box surrounding the face in the image will be displayed. If there are no faces present, a box will not display.

Above the image input form, there is a counter that counts the number of images the user has given to the app.

The user is able to sign out at any time in the top right corner, which will send them back to the sign in page.

# Running the app
The app can be accessed online at [this](https://marko-smart-brain.herokuapp.com/) address.\
(NOTE! The server hosting the website can be a bit slow at times and it may seem like the program is unresponsive, especially when signing in or registering. Please allow a brief interval for the server to execute the instructions)

The app can also be run locally by cloning this repository and running npm start in the terminal. This will start a development server running on port 3000 (by default) of your localhost. If prompted to open the browser, please do so, otherwise you're able to access it manually by typing "[localhost:3000](http://localhost:3000)" in your browser.\
(NOTE! Make sure to install all dependencies by running 'npm install' in the terminal before trying to start the app)

# Easter eggs
The particles in the background are interactive! You will most likely notice this when signing in.

The logo in the corner is also interactive. It tilts whenever hovered over by the mouse.
