# Web API Design 

- An `API` should have these key features 
    - `Platform Independence` 
      - Clients should be able to call the API whenever it is needed 
      - Requires standard protocols 
      - ALso requires where client and web service can agree on format of the data to exchange 
    -  `Service Evolution`
      - API should be able to evolve and update to functionality independently. 
      - Client should be able to work without any modifications 
      - Functionality should not be affected 

- `Rest`
    - Representational State Transfer 
    - Arch style for building distributed systems based on hypermedia 
    - Usually independent but needs HTTP to carry out tasks 
    - Advantage 
        - Uses open standards and does not bind the implementation of the API or the client applications to any specific implementation. 

- `REST APIs` 
    - Designed around resources, any kind of object, data, or service that can be accessed by the client 
    - Has an identifier for the resource
    - Exchanges representations of resources 
    - Has uniform interface, helps to decouple the client and service implementations. 
    - Use stateless required model. 
    - Are driven by hypermedia 

- Organize API around resources 
  - It should be based on nouns and not the verbs 
  - It should be presented to the client as a single entity 
  - Avoid creating APIs that mirror the internal structure of a database 
  - REST is to model entities and its operation in the application to perform thoe entities. 
  - Entities are grouped in collections, a collection is a separate resource from the item within the collection. 
  - An `HTTP GET` request to an items URL returns the details of that item. 
  - It is good practice to organize URLS for collections and items for hierarchy. 
  - `Chatty` web APIs expose large number of small resources which require more requests which will make the brower load time longer which is unwanted. 


- Operations in HTTP Methods 

  -`GET`
    - retrieves representation of the resource at the specificed URL 
  -`POST` 
    - creates new resource at the specificed URL 
  -`PUT`
    - either creates or replaces the resource at the specific URL 
  -`PATCH` 
    - performas partial update 
  -`DELETE` 
    - removes resource at the specificed URL 

- The effect of a specific request should depend on whether the resource is a collection or an individual item. 

- The difference between `POST`, `PUT`, `PATCH`
    - `POST`
      - request creates a resource 
    - `PUT` 
      - request creates a resource or updates an existing resource 
    - `PATCH`
      - request performs a partial update tp an existing resource 

- Request Returns 

  - `GET` successful 
    - 202 (ok)
  - `GET` unsuccessful 
    - 404 (not found)
  - `POST` successful 
    - 201 (created)
  - `DELETE` successful 
    - 204 (created)


## Things I want to know more about 

- I want to see all this happen real time and actually look under the hood of all this processing. 

- I also want to know more about APIs all together



* [Home](Code301Notes.md)