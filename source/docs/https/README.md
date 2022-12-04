# Introduction

## What?

Using the `HTTP/HTTPS` protocol to exfiltrate data from a victim to an attacker's machine requires an attacker 
to have control over a webserver with a server-side programming language installed and enabled. 

## Why?

It is challenging to detect for the blue team if using the POST HTTP method in the data exfiltration (with the GET 
request, all parameters are registered into the log file).

* POST requests are never cached
* POST requests do not remain in the browser history
* POST requests cannot be bookmarked
* POST requests have no restrictions on data length

## How?

* [HTTP data exfiltration](exfil.md)
* [HTTP tunneling](tunnel.md)







