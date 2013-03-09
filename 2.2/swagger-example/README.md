Scalatra Swagger Flowershop
===========================

A sample API, including automatically generated, runnable API documentation,
to demonstrate Scalatra's Swagger functionality.

See the [Scalatra Swagger Guide](http://scalatra.org/2.2/guides/swagger.html)
for more information on using Scalatra with Swagger.

## Build & Run ##

```sh
$ cd 2.2/swagger-example
$ chmod +x sbt
$ ./sbt
> container:start
```

Open your browser to http://petstore.swagger.wordnik.com/, and you'll see the default Swagger demo application - a Pet Store - and you'll be able to browse its documentation. 

The Pet Store documentation is showing because http://petstore.swagger.wordnik.com/api/resources.json is entered into the URL field by default.

Paste http://localhost:8080/api-docs/resources.json - into the URL field, delete the "special-key" key, then press the "Explore" button. You'll see a Swaggerized view of the API documentation for this application. Try clicking on the "GET /flowers" route to expand the operations underneath it, and then entering the word "rose" into the input box for the "name" parameter.

(c) Dave Hrycyszyn, 2013