# registration-ci
User registration and login using CodeIgniter

A simple project to implement user registration and login in codeigniter.

How it works?
User can register, providing email, password, first name and last name. On submit of the form, checks that no field is blank (codeigniter front end validation is used).

If no field is blank, then flash message is displayed in the top of login form.

Sign in link is provided to login with valid credentials.

On logging in, userid and password is stored in session and directs to dashboard, displaying user name.
