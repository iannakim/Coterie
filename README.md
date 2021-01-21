# Coterie

* <a href="https://guarded-escarpment-91959.herokuapp.com/">Live Demo on Heroku </a> 🌎
* <a href="https://youtu.be/nC7PQP0Lf2o"> YouTube demo </a> 🎬

Coterie is a web application that allows users to host and join virtual meetings to connect people with shared interests.	The inspiration of this app came during the time of COVID where it was difficult for people to gather in-person. Coterie provides a safe space to still meet new people and stay connected.	
The word *Coterie*  means a small group of people with shared interests or tastes.	The word *Coterie* means a small group of people with shared interests or tastes.

## Take a Look 📷
<img src='./image/screenshot1.png'> </img>	
<img src='./image/screenshot2.png'> </img>	

## User Features	
### Password Authentication	
 * Validate current users and keeps them logged in using sessions
 * Authenticate users' passwords with BCrypt
 
### CRUD Operations
 Users (the Attendee) can:
  * log into the application
  * create an account
  * see an error message if their account input is wrong
  * register for a meeting
  * view their meetings
  * browse available meetings
  
 User (the Host) can:
  * log into the application
  * create a meeting	
  * change their meetings
  * cancel the meeting
  	  
 ## Set Up
 * Clone down this repo into local machine --git clone <git repository>
 * CD into 'Coterie' application
 * Run 'bundle install' to install all required dependencies
 * Run 'rails db:migrate' to set up the tables for the database
 * Run 'rails db:seed' load data
 * Run 'rails s' to start the server
 * Open the browser and go to 'http://localhost:3000/' to start the app!
 
### Active Record Associations
 * There are 5 models that have the following associations ```has_many, belongs_to and has_many, through: ```
 
## Domain Model
<img src='./image/domainmodel.png'> </img>	
 	 
## Tech Stack	
 * Ruby [2.6.6]
 * Rails
 * PostgreSQL
 * HTML/CSS
 * Active Record
 
## Tools	## Tools
 * Bootstrap
 * BCrypt
 * Custom CSS
 
## Build Status
 * This project was completed in 5 days for the purpose of the project presentation.
 
## Future Features
 * Improve design elements (look of buttons, background image, text manipulation)
 * Create a logo
 * Add About page
 * Utilize API/CSV file for welcome page
 * If a user is a host they can’t be an attendee
 * Allow users to upload a profile picture
 
## Contributors
 * [Anna Kim](https://github.com/iannakim)
 * [Waverley Leung](https://github.com/wlcreate)
 * [Ekaterina Zarudnaya](https://github.com/Elronia)
