# TCP-AND-UDP

This project is  implements Transmission control protocol(TCP) and User Datagram Protocol(UDP) between two branches of a company. The Topology consists of two branches of company( A and B). Each branch is divided into three floors(or LANs) . Two floors consists of systems for communication and a Server floor for access. The Server floor contains three servers : DNS/HTTP , Email, Data . These are Local Servers and can be accessed by the all the systems in the other two floors.  
The communication between two branches takes place with the help of main server which is common to both the branches . The main server also consists of three servers: DNS/HTTP , Email, Data.  These servers can be accessed only by the systems present in the center floor of each branch i.e The communication between different branches of the company can take place only within these systems.

1)  UDP provides connectionless transfer of datagrams between processes in hosts
    attached to the Internet. UDP is simple and fast but provides no guarantees in
    terms of delivery or sequence addressing.
•	The Domain Name System (DNS) is a distributed database that resides in multiple machines on the Internet and is used to convert between names and addresses. Each DNS machine maintains its own database and acts as a DNS server that other machines can query. Typically the requesting machine accesses a local name server, which, for example, may reside in a university department or at an ISP. every machine on the Internet is required to register with at least two authoritative name servers. If a given name server cannot resolve the domain name, the queried name server will refer to another name server, and this process continues until a name server that can resolve the domain name is found.


2) TCP provides for reliable transfer of a byte stream between processes in hosts
      attached to the Internet. TCP is considerably more complex than UDP. TCP involves   the establishment of a connection between the two processes. To provide their service, the TCP  implement error detection and retransmission as well as flow control algorithms.
                                                                                              
•	HTTP is a client/server application to support communications between web browsers and web servers: HTTP defines how the client makes the request for an object and how the server replies with response message. After the user click on a link, the browser program must first resolve the URL to an IP address by invoking the DNS protocol . Once the IP address is returned  the HTTP client must set up a TCP connection to the desired server over well-know port 80 . The HTTP client and server are then ready to exchange messages: the client sends a GET message requesting the document, and the server replies with a response followed by the desired document.
•	SMTP also known as Simple Mail Transfer Protocol, is part of the application layer of the TCP/IP protocol .Here a mail client application interacts with a local SMTP server to initiate the delivery of an e-mail message. The user prepares an e-mail message that includes the recipient's e-mail address, a subject line, and a body. When the user clicks Send, the mail application prepares a file with the above information and additional information


•	File Transfer Protocol (FTP) is another commonly used application protocol. FTP provides for the transfer of a file from one machine to another. Like Telnet, FTP is intended to operate across different hosts. FTP requires two TCP connections to transfer a file. One is the control connection that is established on port 21 at the server. The second TCP connection is a data connection used to perform a file transfer
