# Introduction

## What?

* Tor and domain fronting are also a great way to bypass filters where HTTPS inspection is not looking for a 
mismatch between outer and inner names.
* Many instant message protocols like Skype, Facebook Messenger and IRC can also be leveraged.
* NTP and BGP protocols are often permitted and can be abused to exfiltrate data.
* Remote Desktop can often be used to map drives and the clipboard, and even if these are restricted, data can be sent through the screen.
* X509 certificates can embed binary data which can therefore be used to transmit data.
* Old-school port knocking could also be an option.
* Packet headers can maybe also still be used.
* Are P2P protocols like bittorrent available?

## Why?

The options are near-limitless, just as the neglect over decades. Get creative!

## How?

* [Data Exfiltration With Tor Browser And Domain Fronting](https://blog.didierstevens.com/2018/01/20/quickpost-data-exfiltration-with-tor-browser-and-domain-fronting/)
* [Skype and Data Exfiltration](https://www.sans.org/white-papers/34560/)
* [PyExfil – Python Data Exfiltration Tools](https://www.darknet.org.uk/2016/11/pyexfil-python-data-exfiltration-tools/)
* [pentestpartners/PTP-RAT](https://github.com/pentestpartners/PTP-RAT)
* [fideliscyber/x509](https://github.com/fideliscyber/x509)
* [PORTKnockOut: Data Exfiltration via Port Knocking over UDP](https://www.sans.org/white-papers/37307/)
* [omkartotade/Data-Exfiltration](https://github.com/omkartotade/Data-Exfiltration)






