# SignUp--LogIn
<br/>
Simple Sign In and Log in page using HTML5, CSS, PHP, MySQL
<br/>
This project contains following files/folders - 
<br/> <br/>
1. Main.html (contains html/css/jquery for signup and login). <br/>
2. Signup.php (contain php code for registration of new member). <br/>
3. Login.php (contains php code for login existing member). <br/>
4. Result.html. <br/>
5. Snapshots.

<br/><br/>
1. In "Main.html" I have written HTML , CSS ,Bootstrap , JQuery and AJAX code. The HTML , CSS and Bootsrap are used for designing the Sign up and Log in module. I have created two forms - <br/> <br/>

          - Sign Up form : This form is for registration purpose. If you are a new member then you need
             to enter your details to register.The email id should be unique and should not be used for
             another registration. On submit it will call SignUp.php through ajax call.
          - Login form : This form is for Log in. If you have registered already then you can login by 
            providing email and password. If not registered before then it will show error.On submit it
            will call Login.php through ajax call.
<br/>
2. "SignUp.php"  connects with the database and table present in MySQL and when we submit SignUp form the form data will be stored in database bt using the MySQL insert query.
<br/><br/>
3. "Login.php" contains code for connection to database and it takes input from Login Form and select query will be executed to retreive data of entered email id. If password matches then result will be displayed otherwise it will check for errors and display suitable errors.
<br/><br/>
4. "Result.html" displays the message "Hi.. (username)" when login is successfull.<br/><br/>
5. Snapshot folder contains all the snapshots of the project such as Sign Up form, Login Form, Error if email already exists, Wrong password etc.

