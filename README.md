## Simple HTTP/2 multiplexing demo 

The Web App simply displays a matrix of 400 (20x20) small pictures that compose one large picture.
Just deploy it in a Servlet 4 container and access it via HTTP 1.1 and HTTP/2 (secure port).
Ideally, the connection should be throttled to really show the benefits of HTTP/2 multiplexing.
