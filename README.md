## Laravel Chatify
Simple laravel chat application. It is built with the help of [Laravel Chatify](https://github.com/munafio/chatify) package.
This is the [documentation](https://chatify.munafio.com/) link of this awesome package. It is built using pushers.

## Project setup
Clone this project</br>
Copy .env.example to .env file and make the required changes in .env file
```
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_APP_CLUSTER=
```

## Migration and seed
Run `yarn seed`

## Running the project
Run `yarn api` and `yarn dev`

## Accessing application
- Now visit `http://localhost:8000/register` and create a new account
- Then visit `http://localhost:8000/chatify` and start chatting
