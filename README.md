# How-The-Web-Works
 
What is HTTP?

This is the protocol that is used for communicating between browsers and servers. 

What is a URL?

The specific address on a given server that we're attempting to access via our web browser.

What is DNS?

The global internet phonebook that translates domain names into IP address's for our computer to access a server.

What is a query string?

An additional paramater that can be passed into a URL that usually provides extra info for searching something

What are two HTTP verbs and how are they different?

GET - Search a web server for contain and retrieve data that's already present in the server

POST - Send a request to the server to modify or add additional content

What is an HTTP request?

An action sent by the browser/application to obtain information from a server

What is an HTTP response?

A result from the server based on the request submitted

What is an HTTP header? Give a couple examples of request and response headers you have seen.

A message that lets clients and servers pass information to eachother with an HTTP request or response.
Request Examples: Accept, Accept-Language
Response Expamples: Keep-Alive, Last-Modified, Set-Cookie

What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

The DNS translates the domain name into an IP address. The browser and OS search their cache to see if we've visited this site bfore. If the site is not located at this point
the request gets sent off to the ISP. If it isn't located at this point it is searched through the DNS. In this particular case the sight we attempted to look up had redirected
me to a seperate url.