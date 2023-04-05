- What is HTTP?

>Hyper Text Transfer Protocol outlines the parameters for how clients get data from, or send data to, a server.

- What is a URL?

>Uniform Resource Locator, a URL is an address for some internet resource/page.

- What is DNS?

> Domain Name System, system that takes human-readable URLs and converts them into IP addresses.

- What is a query string?

>The query string lets you pass key-value pairs into the URL, in the format ?key1=value1&key2=value2... which you can later refer to and the browser stores

- List two HTTP Verbs and their use cases.

>GET - get some data from the server (most pages, search forms)
POST - send some data to the server (pages that change data on server)
- What is an HTTP request?

>An HTTP request is a request from a client to a server which follows the HTTP protocol (eg a request for HTML from news.google.com)

-What is an HTTP response?

> HTTP response is a response from a server to a client which follows the HTTP protocol (eg sending back HTML/CSS/JS/etc, generating page)

-What is an HTTP header? Give a couple examples of request and response headers you have seen.

>Headers provide additional information about the request or the response. Here are some examples:
Request headers: Host, User-Agent, Accept, Cookie, Cache-Control
Response headers: Content-Type, Last-Modified, Set-Cookie, Cache-Control

-What happens when you type a URL in a browser?

 >browser decodes the name into an IP address using DNS
 browser makes request to the IP address, w/ headers, cookies etc
 server sends a response 200, 310, 400, etc
 browser creates DOM from the HTML response, and includes other resources like images or js
 browser makes responses for the othe resources too, generates them and includes them in the page as needed