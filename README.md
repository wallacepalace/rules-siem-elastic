# RULES Cybersecurity - Elastic SIEM

Hey there, how are ur?

I'm posting here some rules I made for detecting communications with botnets, command and control (C2), VNC scanners, SSH, MySQL, RDP, DNS, Telnet, HTTP, TFTP. Using honeypots, blacklists, IP rank status, etc. as a base.

The rules were made by me and anyone is allowed to edit them. I'm posting here to help those who don't understand so much about Elastic SIEM or query languages.

The rules were updated today (08/09/2021), but I will try to keep this topic as updated as possible with more rules going forward and always adding new IPs.

It is noteworthy that the rules in question only identify IPs (filebeat, packetbeat, etc). More focused on firewall and proxy logs.

**Observation:**  If u have any problems uploading the rule to your SIEM, change the rule lines where it contains the line below, to the address of your kibana.

> **It looks like this:** {"from":"1m","kibana_siem_app_url":"YOUR-IP-OR-URL-KIBANA/app/security"}

> **Change it to something like this:** {"from":"1m","kibana_siem_app_url":"https://mykibana.com:5601/app/security"}

![image](https://user-images.githubusercontent.com/43219645/132609606-b7a12f92-096a-4aff-a5df-7bb6a2ad26ba.png)

Hope this helps!

> NDJSON archive ready to upload in Elastic SIEM
