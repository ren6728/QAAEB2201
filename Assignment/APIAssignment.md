1.  What is API? Give 3 real-life examples of usage of API.
  Application Programming Interfaces the interface that allows two independent software components to
  exchange information. An API acts as an intermediary between internal software functions and external
  ones, creating an exchange of information so seamless that it often goes unnoticed by the end user.
  EX:surfing the internet by PC or Phone or Ipad; using FB ,TWITTER, WECHAT Paypal apps;
  watching/uploading videos in YOUTUBE or other web apps
2.  What is API testing and name some types of API testing?
  Unit testing, Functional testing,Integration testing, Performance testing,Load testing
3.  What is the difference between REST and SOAP APIs?
  A)SOAP stands for Simple Object Access Protocol;
  SOAP is a protocol which was designed with a specification.
  In SOAP, the WSDL file provides the client with the necessary information which can
  be used to understand what services the web service can offer.
  SOAP can only work with XML format.

  B)REST stands for Representational State Transfer;
  REST is an Architectural style in which a web service can only be treated as a RESTful
  service if it follows the constraints of being:Client Server,Stateless,Cacheable,Layered System,
  Uniform Interface;REST can make use of SOAP as the underlying protocol for web services,
  because in the end it is just an architectural pattern.
  REST permits different data format such as Plain text, HTML, XML, JSON, etc. But the most
  preferred format for transferring data is JSON.

4.  What are common HTTP methods? Explain with examples.
  Most commonly-used HTTP methods are POST(Submit data to a resource and create a new entity),
  GET(Retrieve a URI), PUT(Update all data in a resource entity), PATCH(Update all data in a
  resource entity), and DELETE(Removes all current representations of the target resource given
  by a URI.).
  These methods correspond to create, read, update, and delete (or CRUD) operations, respectively.

5.  What is the difference between POST AND put? Explain with an example.
  PUT method is called when you have to modify a single resource while POST method is called
  when you have to add a child resource.
  PUT method response can be cached but you cannot cache POST method responses.
  You can use UPDATE query in PUT whereas you can use create query in POST.
  In PUT method, the client decides which URI resource should have, and in POST method, the
  server decides which URI resource should have.
  PUT works as specific while POST work as abstract.
  If you send the same PUT request multiple times, the result will remain the same but if you
  send the same POST request multiple times, you will receive different results.
  PUT method is idempotent whereas POST method is not idempotent.

6.  Name 5 main categories of HTTP status codes? Explain 5 status codes from each
category(You have to tell the status code and description of each status code with
an example).
1xx Informational
100	Continue
101	Switching protocols
102	Processing
 2xx Succesful
200	OK
201	Created
202	Accepted
203 Non-Authoritative Information
 3xx Redirection
300	Multiple Choices
301	Moved Permanently
302	Found (Previously "Moved Temporarily")
 4xx Client Error
400	Bad Request
401	Unauthorized
402	Payment Required
403	Forbidden
404	Not Found
405	Method Not Allowed
406	Not Acceptable
407	Proxy Authentication Required
408	Request Timeout
409	Conflict
 5xx Server Error
500	Internal Server Error
501	Not Implemented
502	Bad Gateway
503	Service Unavailable
504	Gateway Timeout
7.  What are the main components of HTTP requests and HTTP responses?
Status Line.
Headers.
Body (Optional)

8.  What are the main components of the HTTP request header and response header?
  An HTTP response header includes information in a text-record form that a Web server
transmits back to the client's browser. The response header contains particulars such
as the type, date and size of the file sent back by the server, as well as information
regarding the server.

9.  What is the difference between authentication and authorization?
  Authentication is the process of verifying who a user is, while authorization is the
  process of verifying what they have access to. Comparing these processes to a real-world
  example, when you go through security in an airport, you show your ID to authenticate
  your identity.

10.  Briefly explain common API Authentication Methods.
  APIs handle enormous amounts of data of a widely varying type – accordingly, one of the
  chief concerns of any data provider is how specifically to secure this data. The idea
  that data should be secret, that it should be unchanged, and that it should be available
  for manipulation is key to any conversation on API data management and handling.

  While there are as many proprietary authentication methods as there are systems which
  utilize them, they are largely variations of a few major approaches. These approaches
  almost always were developed to solve limitations in early communications and internet
  systems, and as such, typically use broad existent architectural approaches with novel
  implementations in order to allow authentication to occur.

  Three major methods of adding security to an API — HTTP Basic Auth, API Keys, and OAuth.