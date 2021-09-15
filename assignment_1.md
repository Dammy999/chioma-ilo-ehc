# The question
What service is rendered on each of the following ports, and how are these services used.

# The answer
<br/><br/>
# Port 20: File Transfer Protocol(FTP) - data transfer port  
# Port 21: File Transfer protocol(FTP) - Control commands

I use the FTP service to upload/download files to/from my VPS

--------------------------------
# Port 22: Secure Shell  (SSH)

I use the SSH service to login to my VPS, and perform administrative operations on the server.

--------------------------------
# Port 23: Telnet protocol

I use the telnet protocol to configure my TP-link router.
From my own experience, this service is a little bit similar to the SSH service, but its unencrypted.

--------------------------------
# Port 25: Simple Mail Transfer Protocol (SMTP)

It's use to send mail to a mail server (e.g. mail.google.com) from a mail client (e.g. Thunderbird)

--------------------------------
# Port 53: Domain Name System (DNS)

The DNS service converts the human readable domain names to IP addresses that the TCP/IP protocol suite can work with (e.g. techietude.com sent to a DNS resolver gave me the IP: 172.67.180.14)

--------------------------------
# Port 67: Bootstrap protocol server / DHCP

# Port 68: Bootstrap protocol client / DHCP

The DHCP service is use to dynamically assign an IP address to a device that's just joining a network. 
DHCP is used when the static IP address allocation option is not used. 
 
--------------------------------
# Port 80: Hypertext Transfer Protocol (HTTP)

This protocol is used to exchange data between a web server and a web browser.
Almost all modern web browsers use this protocol.

--------------------------------
# Port 110: Post office protocol (POP)

It's a service that's used to synchronise mail between a mail server and a mail client

--------------------------------
# Port 123: Network Time Protocol (NTP)

This protocol is used by computers to synchronize themselves with the current global time and date, without the help of a human being.
I use it on some of my internet connected Arduinos to get the current timestamp, when they boot up.

--------------------------------
# Port 443: HTTPs

The TLS (or SSL) facilitated version of the HTTP service is served on this port.
In other words, any data that's exchanged through this port is end to end encrypted.

--------------------------------
# Port 143: Internet Message Access Protocol (IMAP)

It's used to synchronise mails between a mail server and a mail client.
