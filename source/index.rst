Data exfiltration
=============================================

Data exfiltration is a non-traditional approach for copying and transferring data from a compromised to an
attacker's machine. The data exfiltration technique is used to emulate the normal network activities, and
relies on common network protocols such as DNS, HTTP, SSH, etc.

Data exfiltration over common protocols is challenging to detect and distinguish between legitimate and malicious
traffic.

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: THM Lab

   docs/infra.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: TCP

   docs/tcp/README.md
   docs/tcp/exfil.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: SSH

   docs/ssh/README.md
   docs/ssh/exfil.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: HTTP(S)

   docs/https/README.md
   docs/https/exfil.md
   docs/https/tunnel.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: ICMP

   docs/icmp/README.md
   docs/icmp/exfil.md
   docs/icmp/c2.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: DNS

   docs/dns/README.md
   docs/dns/conf.md
   docs/dns/exfil.md
   docs/dns/tunnel.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Other ways

   docs/other/README.md
   Data Exfiltration With Tor Browser And Domain Fronting <https://blog.didierstevens.com/2018/01/20/quickpost-data-exfiltration-with-tor-browser-and-domain-fronting/>
   Skype and Data Exfiltration <https://www.sans.org/white-papers/34560/>
   PyExfil – Python Data Exfiltration Tools <https://www.darknet.org.uk/2016/11/pyexfil-python-data-exfiltration-tools/>
   pentestpartners/PTP-RAT <https://github.com/pentestpartners/PTP-RAT>
   fideliscyber/x509 <https://github.com/fideliscyber/x509>
   PORTKnockOut: Data Exfiltration via Port Knocking over UDP <https://www.sans.org/white-papers/37307/>
   omkartotade/Data-Exfiltration <https://github.com/omkartotade/Data-Exfiltration>

.. toctree::
   :caption: Links

   Red Team <https://tymyrddin.github.io/red/>
