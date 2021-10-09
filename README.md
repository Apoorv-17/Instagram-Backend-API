Name: Apoorv Yadav
Reg. No: 19BCE1163

# Task  | Instagram Backend API
A simple Golang backend application that demonstrates the use of JWT tokens for users.

The task is to develop a basic version of aInstagram. You are only required to develop the API for the system. Below are the details.

You are required to Design and Develop an HTTP JSON API capable of the following operations,
* Create an User
  * Should be a POST request
  * Use JSON request body
  * URL should be ‘/users'
* Get a user using id
  * Should be a GET request
  * Id should be in the url parameter
  * URL should be ‘/users/<id here>’
* Create a Post
  * Should be a POST request
  * Use JSON request body
  * URL should be ‘/posts'
* Get a post using id
  * Should be a GET request
  * Id should be in the url parameter
  * URL should be ‘/posts/<id here>’
* List all posts of a user
  * Should be a GET request
  * URL should be ‘/posts/users/<Id here>'



## Running Locally

Setup your .env file locally to hold the port and the DB connection string

```sh
$ git clone https://github.com/Joojo7/user-athentication-golang.git
$ cd user-athentication-golang
$ go build -o new -v 
$ ./new
```

The application should be available and running on [localhost:8000](http://localhost:8000/).

