# Express REST API

## classes

### 1-Classes are a template for creating objects 

### 2- Can a class declaration be hoisted?

>no they can't

### How would you describe a constructor and contextual “this” to a non-technical friend?

>a constructor is the method which creates the object and initialze it and you can't use multple methods with the same name as it in the class

## Using Express Routing

### Within Express, what does routing refer to?

> refers to how an application endpoint respond to a user or client request

### What is the difference between a route path and a route method?

> the path is what the url which the user requests and the endpoint  ,the method is the code to get executed when the user hits and requests that path

### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

> use next when you want to hit a next middleware or throw a error which is after the specified route , when next is passed you first do the operation you want then call next to hit the next middleware or next route 

## What is an Express Router?

> routes is like a mini express aplication for a dedicated route.

## By what mean do we initialize express.Router() in an express server?

> it means that we want to create a new instance  router with the routes we will add to it

## What do we use route middleware for?

> to specify a middleware to be run before  the request is processed  for that exact router

### Reflection

>i tried to use express router before in my prep-project but it didn't work like i wanted ,database operations wern't working and i needed to connect to database on each route ,i want to learn how i can avoide that issue 

## Things I want to know more about

### using router with sql and no sql

