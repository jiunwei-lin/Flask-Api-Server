# Flask-Api-Server
Web API Development with FLASK
---
In recent years REST (REpresentational State Transfer) has emerged as the standard architectural design for web services and web APIs.

In this article I'm going to show you how easy it is to create a RESTful web service using Python and the Flask microframework.

*What is REST?
The characteristics of a REST system are defined by six design rules:
  *Client-Server: There should be a separation between the server that offers a service, and the client that consumes it.
  *Stateless: Each request from a client must contain all the information required by the server to carry out the request. In other words, the server cannot store information provided by the client in one request and use it in another request.
  *Cacheable: The server must indicate to the client if requests can be cached or not.
  *Layered System: Communication between a client and a server should be standardized in such a way that allows intermediaries to respond to requests instead of the end server, without the client having to do anything different.
  *Uniform Interface: The method of communication between a client and a server must be uniform.
  *Code on demand: Servers can provide executable code or scripts for clients to execute in their context. This constraint is the only one that is optional.
