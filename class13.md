## Status Codes Based On REST Methods

- In your own words, describe what each group of status code represents:
100’s = that the header part of the request has been received and the server will try to comply with a transmission demand of the client.

200’s =ok , These are the success codes. 
300’s =These are redirection codes , the resource is not avaliable at this location.

400’s = error codes,They are all about invalid requests a client sent to a serve
500’s = server error codes. 


- What is a status code 202?
that it met all validation requirements at the time of sending.


- What is a status code 308?
This tells the client to use another URL to access the resource and not use the current URL anymore.

- What code would you use if an update didn’t return data to a client?
204 No Content 

- What code would you use if a resource used to exist but no longer does?
410 Gone

- What is the ‘Forbidden’ status code?
The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.