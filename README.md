# 2021 AUTH0 + JWT + MYSQL
#### [IS219 Final] Yu-Ching Tseng
#### Use Auth0 universal login, generate JWT to secure profile and db routes

## ScreenShots 

- This is the page you see before login: <br />
![page](https://github.com/yt249/is219-finalproject/blob/master/img/main%20page.png)

- This is the auth0 page user login: <br />
![page](https://github.com/yt249/is219-finalproject/blob/master/img/auth0.png)

- This is the first page user will see after login: <br />
![page](https://github.com/yt249/is219-finalproject/blob/master/img/login%20page.png)

- This is the personal profile page user can see after login: <br />
![page](https://github.com/yt249/is219-finalproject/blob/master/img/profile.png)

- This is the db page user can see after login: <br />
![page](https://github.com/yt249/is219-finalproject/blob/master/img/db.png)

- Both profile and db pages are secured by JWT(shown in console for test purpose) <br />
![page](https://github.com/yt249/is219-finalproject/blob/master/img/authenticate%20and%20jwt.png)

## JWT successfully block a un-authorized login
**Red**: successfully get a token after login <br />
**Green**: if the user hasn't login, and attempt to browse to localhost:3000/user, there is no JWT detected, thus, redirect the user to the login page <br /> 
![page](https://github.com/yt249/is219-finalproject/blob/master/img/fail.png)