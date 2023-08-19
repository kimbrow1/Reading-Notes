# Reading

## Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:
100’s =the initial part of the request has been received by the server and that the client should proceed with the request or ignore the response if the request has already finished
200’s = It is an ok status meaning it was successful
300’s = the request has more than one possible response
400’s =error caused by an invalid request
500’s = the server has encountered an unexpected condition or configuration problem that prevents it from fulfilling the request made by the browser or client
What is a status code 202?the request has been accepted for processing, but the processing has not been completed
What is a status code 308? the resource requested has been definitively moved to the URL given by the Location headers
What code would you use if an update didn’t return data to a client? 204 No Content - A proper code for updates that don't return data to the client, for example when just saving a currently edited document
What code would you use if a resource used to exist but no longer does? This response code is like 404 (“Not Found”), but it provides a little more information
What is the ‘Forbidden’ status code? you don't have permission to access this resource' is displayed when a web server recognizes a user's request but is unable to allow additional access

# Videos

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

Why do we need to pull our MongoDB database string out of our server and put it into our .env? So that the data would not be present to the public and protected 
What is middleware? Middleware is a type of computer software that provides services to software applications beyond those available from the operating system
What does app.use(express.json()) do? s to parse incoming JSON data from HTTP requests, a standard format for data transmission in web servers
What does the /:id mean in a route? the path that gets you to this function
What is the difference between PUT and PATCH? PUT is a technique of altering resources when the client transmits data that revamps the whole resource
How do you make a default value in a schema? Your schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in
What does a 500 error status code mean? the server encountered an unexpected condition that prevented it from fulfilling the request.Apr 10, 2023
What is the difference between a status 200 and a status 201? 200: “Everything is OK.” This is the code that is delivered when a web page or resource acts exactly the way it's expected to. 201: “Created.” The server has fulfilled the browser's request, and as a result, has created a new resource

