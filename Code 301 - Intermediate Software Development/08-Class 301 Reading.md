
# API Design Best Practices

What does REST stand for? Representational State Transfer
REST APIs are designed around a ___HTTP requests to access and use data.
What is an identifier of a resource? Give an example. Uniform Resource Locator (URL)
What are the most common HTTP verbs? he primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, and DELETE
What should the URIs be based on? What the website represent
Give an example of a good URI. “https://www.example.com/index.html”
What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? any API that requires consumer to do more than a single call to perform a single, common operation
What status code does a successful GET request return? The 200 OK status code means that the request was successful, but the meaning of success depends on the request method used: GET: The requested resource has been fetched and transmitted to the message body.
What status code does an unsuccessful GET request return? The 422 (Unprocessable Entity) status code means the server understands the content type of the request entity (hence a 415 (Unsupported Media Type) status code is inappropriate), and the syntax of the request entity is correct (thus a 400 (Bad Request) status code is inappropriate
What status code does a successful POST request return? The 201 Created status code means that the request was successfully fulfilled and resulted in one or possibly multiple new resources being created.
What status code does a successful DELETE request return? A successful response of DELETE requests SHOULD be an HTTP response code 200 (OK) if the response includes an entity describing the status.

