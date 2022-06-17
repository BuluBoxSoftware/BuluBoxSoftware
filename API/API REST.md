<h1 align="center"> REST API (Application Programming Interface)</h1>

**API**: An API is a set of definitions and protocols for building and integrating application software. It’s referred as a connection between an information provider and an information user—establishing the content required from the consumer (the call) and the content required by the producer (the response). API's alllows users to do testing without touching the GUI (Graphical User Interface) or live database of a website. It is important to state that API's are used in a number of applicationes (funtionality testing, load testing, security testsing, penetration testing, navigate testing etc).

**REST**: REST is a set of architectural constraints, not a protocol or a standard. When a client request is made via a RESTful API, it transfers a representation of the state of the resource to the requester or endpoint. This information, or representation, is delivered in one of several formats via HTTP: JSON (Javascript Object Notation), HTML, XLT, Python, PHP, or plain text. JSON is the most generally popular file format to use because, despite its name, it’s language-agnostic, as well as readable by both humans and machines [1]. 

**Headers**: Are part of the API request and response as they represent the meta-data associated with the API request and response. Headers carry information for:  Request, Response, Body and Authorization.

**Parameters**:  Are the variable parts of a resource. They determine the type of action you want to take on the resource. Each parameter has a name, value type ad optional description. Whenever you want to build a REST API, you have to decide which parameters should be present in the API endpoint.

**Authorization**: Authorization are used to ensure that client requests access data securely. This can involve authenticating the sender of a request and confirming that they have permission to access or manipulate the relevant data. In some cases Base64 encoding schemes are used in authorization when there is a need to encode binary data that needs to be stored and transferred over media that are designed to deal with ASCII [2].

**Langaunges**:
API testing can be done in a number of programming lanuanges, the following are some pratical languages used for API testing [3]: 

<ul>
  <li>XML</li>
  <li>JSON</li>
  <li>PHP</li>
  <li>Python</li>
  <li>GraphQL</li>
</ul>  

----------------------------------

**HTTP**: Hypertext Transfer Protocol as the communication protocol between the two systems. HTTP expose endpoints as gateways for HTTP requests to have access to a server.The following are the types of http request a user can make [4]:<br>

<ul>
  <li>GET: Are the most common and widely used methods in APIs and websites. Simply put, the GET method is used to retreive data from a server at the specified resource</li>
  <li>PUT: Are used to send data to the API to update or create a resource</li>
  <li>POST: Used to send data to the API server to create or update a resource </li>
  <li>DELETE: Used to eliminate a resource from the server </li>
  <li>UPDATE: Modify or update a specific request</li>
</ul>  

<p align="center">
<img src=https://github.com/SoftwareBulu/TechDocumentation/blob/main/API/API%20Architecture.png>
</p>

**Response Codes** 

200: OK. Everything worked as expected.<br>
201: A resource was successfully created in response to a POST request.<br>
204: The request was handled successfully and the response contains no body content (DELETE request).<br>
304: The resource was not modified. You can use the cached version.<br>
400: Bad request. This could be caused by various actions by the user, such as providing invalid JSON data in the request body etc.<br>
401: Authentication failed.<br>
403: The authenticated user is not allowed to access the specified API endpoint.<br>
404: The requested resource does not exist.<br>
405: Method not allowed. Please check the Allow header for the allowed HTTP methods.<br>
415: Unsupported media type. The requested content type or version number is invalid.<br>
422: Data validation failed (in response to a POST request, for example). Please check the response body for detailed error messages.<br>
429: Too many requests. The request was rejected due to rate limiting.<br>
500: Internal server error. This could be caused by internal program errors.<br>

<p align="center">
<img src=https://github.com/SoftwareBulu/TechDocumentation/blob/main/API/Response%20Code.png>
</p>

**Summary**: A great testing tool to practice and learn API testing (requests and response) is the following [5].

**References**

[1] https://www.redhat.com/en/topics/api/what-is-a-rest-api <br>
[2] https://www.base64encode.org/<br>
[3] https://www.programmableweb.com/news/what-programming-language-most-popular-apis/2013/06/03<br>
[4] https://blog.postman.com/intro-to-apis-what-is-an-api/<br>
[5] https://gorest.co.in/ <br>

<h5 align="center"> Copyright (C) 2022 by BuluBox. All rights reserved</h5>
