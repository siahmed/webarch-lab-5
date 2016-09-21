# Lab 5
Using the terminal to browse the web

## In this lab you will accomplish the following
 - Use the terminal to browse the web
 - Explore different status code

## First install curl in your virtual machine
 - Open the terminal
 - Enter the following command to install curl: ```sudo apt install curl```

## Open the terminal and use the application "curl"
 - Open the terminal
 - The usage of curl is: ```curl -v "[url]"```
 - For example, entering ```curl -v "https://google.com"``` would have the subsequent result:
```
* Rebuilt URL to: http://info253.p2ptrainer.com/
*   Trying 74.50.7.240...
* Connected to info253.p2ptrainer.com (74.50.7.240) port 80 (#0)
> GET / HTTP/1.1
> Host: info253.p2ptrainer.com
> User-Agent: curl/7.47.0
> Accept: */*
> 
< HTTP/1.1 200 OK
< Date: Wed, 21 Sep 2016 05:46:01 GMT
< Server: Apache/2.4.16 (Unix) OpenSSL/0.9.8e-fips-rhel5 mod_bwlimited/1.4 mod_fcgid/2.3.9
< Last-Modified: Tue, 20 Sep 2016 05:37:12 GMT
< ETag: "24f-53ce9d202d200"
< Accept-Ranges: bytes
< Content-Length: 591
< Content-Type: text/html
< 
<!DOCTYPE html>
<html>
...
``` 

## Answer the following questions in a text file called "answers.txt" at the root of this repository
  - For the domain info253.p2ptrainer.com using the scheme "http" 
    - What is the return code for the path /index.html?
    - What is the return code for the path /aboutus.html?
    - What is the return code for the path /contactus.html?
        - If the path /contactus.html for the given domain was entered into the browser what would happen? Write down the curl command that would simulate the HTTP request the browser would execute.
 - What is the return code for http://www.google.com/teapot?
 - What is the curl command to do a google search for the term "webarch"? Hint: go to [Google](https://google.com) do a search and see what happens on the address bar

