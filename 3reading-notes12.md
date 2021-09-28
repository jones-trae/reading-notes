##Reading Notes 12
1. In your own words, describe what each group of status code represents:
    * 100’s =information, early failure, body doesn’t load, usually problem with header ex.
    * 200’s =request was validated, not necessarily success
    * 300’s =redirect; location invalid
    * 400’s =client error; timeouts, wrong URI, missing authentication
    * 500’s =server error; overloaded or unreachable
2. What is a status code 202? Accepted, processing will be done in the future, usually an asynchronous status code
3. What is a status code 308? Permanent redirect
4. What code would you use if an update didn’t return data to a client? 204
5. What code would you use if a resource used to exist but no longer does?204?!?
6. What is the ‘Forbidden’ status code? 403

##Build A REST API With Node.js, Express, & MongoDB - Quick
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env? Because they dont get installed at inception and to not have to rerun every change made
2. What is middleware? Code that runs between req/ret
3. What does app.use(express.json()) do? Lets server accept json as a body
4. What does the /:id mean in a route? Parameter
5. What is the difference beween PUT and PATCH?put updates everything, patch just what is passed
6. How do you make a defalut value in a schema? empty string
7. What does a 500 error status code mean? Server error
8. What is the difference between a status 200 and a status 201? Both mean request was validated but 201
## Things I want to know more aboutWHY  DO WE NOT WATCH THIS VIDEO AT THE BEGINNING OF LAST WEEK?

[Back](README.md)