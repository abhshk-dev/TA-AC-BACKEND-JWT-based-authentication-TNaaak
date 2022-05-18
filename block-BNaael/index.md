writeCode

Create an  express  application where

- implement login/registration for users using email/password

- implement JWT based authentication
  - after user logs in, send him JWT token
  - when request comes for protected routes, implement JWT verification

We have 2 routes when we gererate express app i.e.

- `/` index route
- `/users` route

Add routes for login/registration

- POST '/users/login'
- POST '/users/register'

After implementing JWT authentication

- keep `/` route open
- protect `/users` route for authenticated user only
