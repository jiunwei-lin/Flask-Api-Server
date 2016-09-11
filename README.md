
# Web API Development with FLASK

> In recent years REST (REpresentational State Transfer) has emerged as the standard architectural design for web services and web APIs.
>
> In this article I'm going to show you how easy it is to create a RESTful web service using Python and the Flask microframework.

## What is REST?
The characteristics of a REST system are defined by six design rules:
  * Client-Server: There should be a separation between the server that offers a service, and the client that consumes it.
  * Stateless: Each request from a client must contain all the information required by the server to carry out the request. In other words, the server cannot store information provided by the client in one request and use it in another request.
  * Cacheable: The server must indicate to the client if requests can be cached or not.
  * Layered System: Communication between a client and a server should be standardized in such a way that allows intermediaries to respond to requests instead of the end server, without the client having to do anything different.
  * Uniform Interface: The method of communication between a client and a server must be uniform.
  * Code on demand: Servers can provide executable code or scripts for clients to execute in their context. This constraint is the only one that is optional.

![N|Solid](http://akamaicovers.oreilly.com/images/0636920050339/cat.gif)

```sh  
Web API Development with Flask
By Gergo Bogdan
Publisher: Packt Publishing
Final Release Date: January 2016
```

## Master RESTful API development with Python and Flask

Building good web APIs is not an easy task, but is a necessity for applications that support multiple platforms (mobile, tablet, and web applications) especially with the modern, mobile-first approach to development. In this course, you will learn how to build up and structure an effective web API that can be used by any client application accessing it over the HTTP protocol.

We will start out with basics of the Flask framework before establishing a comprehensive foundation of working with CRUD operations using SQLAlchemy and MySQL as the data store. You’ll get an understanding of how REST works relative to APIs, and we’ll cover how to test APIs written in Python with the support of Flask. You will learn about token-based authentication and find out how to store passwords securely in your database. Best practices and design guidelines when building large applications are also presented.

After completing Web API Development with Flask, you will have enhanced your technical knowledge about RESTful web APIs and have absorbed best practices that can be applied practically in the future.

## Who this course is for

This video is for web developers who want to build RESTful web APIs using Flask with Python. Developers should be familiar with Python and basic web concepts, such as HTTP verbs and JSON, and should possess basic database knowledge in order to understand SQLAlchemy concepts.

## What you will learn from this course

* Understand the fundamental capabilities of the Flask framework
* Find out how HTTP/Verb methods are used for CRUD operations
* Become efficient using SQLAlchemy to store and query data models
* Design and develop large applications independently from Flask
* Integrate and develop authorization mechanisms in web APIs
* Explore security principles, and understand how storing passwords should be implemented
* Use the Flask test client efficiently to run automated tests

## Table of Content
---
* Getting Up to Speed with Flask
  * The Course Overview
  * Setting Up Flask and Creating Your First Flask Application
  * Custom Routing Configuration
  * Flask Template Usage
  * Flask Flash Messages and Custom Error Pages

* Implementing Create and Read through a RESTful API
  * CRUD and REST Basics
  * Using SQLAlchemy for Model Mapping
  * Implementing Create
  * Implementing Read

* Implementing Update and Delete through a RESTful API
  * Implementing Update
  * Implementing Delete
  * Hypermedia
  * Implementing Pagination
 
* Extending the Web API
  * RESTful Authentication
  * HTTP Caching
  * Error Handling in RESTful APIs
  * Guidelines for Building Large Projects
 
* Securing Web APIs
  * Why Use HTTPS?
  * Token Authentication
  * Usage of Cookies
  * Storing Passwords 03m  48s
 
* Testing Web APIs
  * Using the Flask Test Client
  * Testing Custom Flask Routes
  * Testing CRUD
  * Testing Authentication
