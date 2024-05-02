# E-0923 NodeJS Cookies Exercise

Goal: Create a working login form using NodeJS and Express as the backend and NextJS as the frontend

Demo: [https://drive.google.com/file/d/1hPTh4I58dv5fH3m9h2oUeGMCjJA3uSFe/view?usp=sharing]

1. Set up your backend server using NodeJS and Express
2. Set up your frontend using NextJS
3. On your backend server, create an in-memory database of users with the username as 'admin' and password is 'admin12345'
4. Make sure you have these 3 routes in your NextJS app:

   - Home page (/) - Can just have dummy text
   - Login page (/login) - Login form
   - My Profile (/profile) - Can just have dummy text

5. A user who is not logged in cannot access the `/profile` page and will be redirected to the `/login` page
6. On the login page, you will have a form with a username and a password field. When a user logs in, the login information will be sent to the backend server as a POST request. If the login is valid, the backend server will set a cookie with the username
7. Once you are done, push your changes to `dev` and merge `dev` to `master` branch
