# we-blog

>  The best™ blogging platform in the world

## Install
Server:
```bash
$ cd server 
$ npm install
```
Client:
```bash
$ cd client
$ npm install
```

## Run
Server:
```bash
$ cd server
# Run server on http://localhost:8000
$ npm start
```
Client:
```bash
$ cd client
# Run client on http://localhost:3000
$ npm start
```

## API
### Posts
Get all posts:
```
GET  /posts
```
Find a post by ID: 
```
GET  /posts/{id}
```
Create a new post:
```
POST  /posts
```
Update an existing post:
```
PUT  /posts/{id}
```
Delete a post:
```
PUT  /posts/{id}
```
