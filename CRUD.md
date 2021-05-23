# Status Codes Based on REST Methods 

- `Status Code`
  - Number higher than 100 and smaller than 600 that is part of a HTTP response. 
    - The first digit defines the class of the status. 

- `Status Classes`
    - `100-199`
      - Tells the client that their request will fail at the top section before even getting to other parts of the code
    - `200-299`
      - Tells the client or user that the code was successful and there was no issues with the requests 
      - Asycn code is a bit different (202) it only met validation requirements at the time of sending. 
    - `300-399`
      - Redirects the client and explains that the information requested is not in the desired location where they believed the information was located at intitially. 
    - `400-499`
      - Client error codes, they entail invalid requests which could occur for multiple reasons such as the wrong URI or missing authentication. 
    - `500-599`
      - Server error codes, this usually means the server at the time of request can handle the request due to issues on the server side. 

- `CRUD` 
  - Stands for CREATE, READ, UPDATE, and DELETE


- `308`
  - This status code is a permanent redirect and should give the client the new URL to go where the information is now located

- `406`
  - This status code indicates that the client needs an update and acts like a 404 however the URL does still exist but does not due to the lack of the update. 

- `410` 
  - Indicates that the resource existed but no longer does. 

- `403`
  - Forbidden status code indicating that the client has no permissions to access the information or resource 


## Things I want to know more about

- I want to actual come across these various status codes and actually see them in live.