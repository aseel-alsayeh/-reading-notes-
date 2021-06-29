## RESTful web API design

- What does REST stand for?
`Representational State Transfer`

- REST APIs are designed around a ____.
  resources.

- What is an identifer of a resource? Give an example.
a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:HTTP
https://adventure-works.com/orders/1

- What are the most common HTTP verbs?
The most common operations are GET, POST, PUT, PATCH, and DELETE.

- What should the URIs be based on?
 based on nouns (the resource) and not verbs (the operations on the resource)

- Give an example of a good URI.
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
What status code does a successful GET request return?
What status code does an unsuccessful GET request return?
What status code does a successful POST request return?
What status code does a successful DELETE request return?