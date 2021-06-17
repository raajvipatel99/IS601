## HTML and HTTP

- How to computers communicate ? What is the functioning of web browser ?  
- When you type web address, URL (Universal Resource Locator) in web browser your computer makes a Get Request to the server which may be a thousand miles away and asks for the HTML (Hypertext Markup Language) code.
- HTML basically tells how a webpage should look. Text is included directly in HTML but there is a separate URL for each audio, video or image embedded. Hence a separate HTTP request is generated for each of them.
- Get request is basically used when your computer is trying to “get” data from the server.  
- Similarly, when you fill a form or in any way try to send your data to the server, Post Request is used. The difference between get and post request is that get is used to get the data while post is used to send the data.
- The server sends Cookie data that the browser stores which acts like an ID. Whenever the next request is generated, the browser automatically attaches that ID with the request.
- Since we know that internet is all about open connections and information sent as plain text, Transport Layer Security (TLS), Secure Socket Layer (SSL) (security protocols) acts as a layer of security wrapped around the communication to prevent tampering.
- Digital certificates can be called an official ID for proving authenticity. 
- When a browser asks a website to engage in secure connection, it sends a digital certificate. 
- A digital certificate is published by the certificate authorities that identifies websites and issues certificate for them. When a website tries to start a secure connection without a digital certificate, your browser warns you.
