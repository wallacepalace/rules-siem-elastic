# RULES Cybersecurity - Elastic SIEM

Hey there, how are ur?

I'm posting here some rules I made for detecting communications with botnets, command and control (C2), VNC scanners, SSH, MySQL, RDP, DNS, Telnet, HTTP, TFTP. Using honeypots, blacklists, IP rank status, etc. as a base.

The rules were made by me and anyone is allowed to edit them. I'm posting here to help those who don't understand so much about Elastic SIEM or query languages.

The rules were updated today (08/09/2021), but I will try to keep this topic as updated as possible with more rules going forward and always adding new IPs.

It is noteworthy that the rules in question only identify IPs (filebeat, packetbeat, etc). More focused on firewall and proxy logs.

Hope this helps!

NDJSON archive ready to upload in Elastic SIEM
