# Introduction

## What?

DNS tunneling establishes a communication channel where data is sent and received continuously.

## Why?

Since ``DNS`` is not a transport protocol, many organisations do not regularly monitor the DNS protocol. 
The `DNS` protocol is allowed in almost all firewalls in any organisational network, although good organisations 
will have monitoring in place to detect it afterwards. The fabulous `dnscat2` is very easy to get up and running.

Some IDS/IDPs are now capable of spotting DNS tunnelling, but often miss data sent via DNS TXT records. Re-useful tools
are [Uninvited-Guest](https://github.com/pentestpartners/Uninvited-Guest), and its earlier, more raw version 
[DNSTXT-encoder](https://github.com/pentestpartners/DNSTXT-encoder).

## How?

* [DNS configurations](conf.md)
* [Exfiltration over DNS](exfil.md)
* [DNS tunneling](tunnel.md)






