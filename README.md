# CS-305-Artemis-Financial-Practices-for-Secure-Software-Report

    The client for this particular assignment is Artmeis Financial, 
a finance company seeking a secure website to transact its patron's 
funds. To accomplish this, I inplemented the secure protocol AES-256 
CBC to hash user data before sending it over the internet to and from 
the server. This will prevent any hackers who might intercept the data 
from being able to read it. This protocol stands uncracked so I am 
sure I will see it and use it for many more future projects. To ensure 
both parties are legitimate, certificates are used to validate their 
identities. These certificates are stored in user authenticated keystores 
for the program/system to access when authentication is neccessary. 
After each implementation, another vulnerability assessment was conducted 
to ensure no new vulnerabilities were introduced. In this project, I 
used the native Java keytool program to generate my own self-signed 
certificates, which will be useful when creating new applications and 
websites for clients. Overall, I am most proud of my understanding of 
certificates and how to generate them. Security is important on the web 
and ensuring you know how to authenticate your program is vital in secure 
communications.
