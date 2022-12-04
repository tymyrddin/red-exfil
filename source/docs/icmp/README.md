# Introduction

## What?

Data exfiltration can also leverage ICMP flows with a C2 server, using the data payload in ICMP-PING packets.

## Why?

The detection of data exfiltration using this method is not easy since it’s hard to tell apart "normal", legit 
ICMP traffic from ICMP flows part of an exfiltration attempt. Furthermore, some tools used for endpoint telemetry, 
such as Sysmon, record TCP/UDP connections but not ICMP flows.

## How?

* [ICMP Data Exfiltration](exfil.md)
* [ICMP C2 Communication](c2.md)






