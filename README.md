# Peyvand
A simple backend for social media application built using FastAPI with user authentication and basic social features.

## Features

### User Management
- Register new users
- Login with JWT authentication

### Posts
- Create, Read, Update, Delete posts
- Each post has a title and description

### Likes & Comments
- Users can like posts
- Users can comment on posts


## Tech Stack
- FastAPI
- SQLAlchemy
- SQLite
- JWT
- Docker

## Run locally
Use the following commands to build and run the project on your local machine:

```
docker build -t peyvand . 
docker run -d --name peyvandContainer -p 80:80 peyvand
```

you can access the swagger docs in [http://localhost/docs](http://localhost/docs)

