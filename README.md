# Instagram-clone-with-FLASK
A FullStack Instagram App built with Flask and React. 


## Technologies_and_Tech_stack_involved
- Python
- light weight sqlite database
- Flask
- JWT (token authentication)

## About_this_App
- An Instagram clone build with Flask,bootstrap v5, Html & Css  
- Allows users to share, comment, posts or create their own. 
- follow or get connected with other users and more functionalities within the app to discover.

### Home_page
This page displays posts of all users in the database.

### Single_post_page
This page displays the complete details about the post (like about, liked by, comments etc.)

### home-feed
At this page you can see posts, made by all the signed up users in the application (global posts in short).

### Your_Profile_Page
Here you can manage your profile information like your profile picture (which you can update), your posts, followers and the people you are following.
Also, just like instagram can also visit other peoples profile as well.

### Login_Page
<p align="center">
  <img width="50%" height="auto" src="https://i.ibb.co/F3dbVq9SD/login-page.png">
</p>

### Sign_up_page
<p align="center">
  <img width="50%" height="auto" src="https://i.ibb.co/M81Ppk2/sign-up-page.png">
</p>

## Short_Note
The program is a demonstration of my acquired skills for the period I have been in the ALX program. I have integrated the CRUD system, user registration, authentication and deleting of post and comments 


### Backend

- create your virtual environment
`python -m venv myenv` 

- activate your virtual environment
`myenv\scripts\activate`

- install project dependencies
`pip install -r requirements.txt`

- create your flask database
`flask db init`

- make your first migration
`flask db migrate -m "create tables"`

- upgrade or update your database
`flask db upgrade`

- run the project
`flask run`

- open a new terminal window follow below commands(keep the application running)

`flask shell`

- As your application is entirely new so there is no data in it so go ahead and signup and login to create your new account 

* Note: if the application is not recognizing localhost then use its address instead like this => `http://127.0.0.1:5000/login`, make sure to not include extra slashes "/" at the end of your endpoint or api to avoid not found issues, please use the urls as mentioned in views.


<p><a href="#top">Back to Top</a></p>
