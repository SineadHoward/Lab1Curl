Question2
cURL, which stands for client URL and can be written as curl (which I’ll do for the remainder of the blog because I’m lazy), 
is a command line tool for file transfer with a URL syntax. It supports a number of protocols including HTTP, HTTPS, FTP, and many more. 
HTTP/HTTPS makes it a great candidate for interacting with APIs!

curl can be used on just about any platform on any hardware that exists today. 
This means, regardless of what you are running and where, the most basic curl commands should just work. None of the usual “it doesn’t work on my machine”.

Question3
curl -v https://odetocode.com/odetocode.jpg

HTTP Request
> GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*

HTTP Response
< HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Mon, 16 Sep 2019 09:28:02 GMT
<

Question 8 

https://www.independent.ie/
291 requests