# DreamNexus

this is the repo for http://www.dreamex.us

for maintainers, contributors, and just those that are curious.
Bootstrap 4.0

# Compile Less
To compile Less to Css for this project, make sure you have Nodejs installed. Then install less and nodemon globally by typing this into your console: `npm i -g nodemon less`. _This is shorthand for npm install --global nodemon less_

To compile once run the following command: `lessc less/index.less css/index.css`

To compile on save run the following command: `nodemon --exec lessc less/index.less css/index.css`
