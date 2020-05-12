# sliit
# My Assignment 
Software Security
OAuth 2.0 framework Authorization Process (May 2020)

H M P K Ranjan Kumara Herath
Faculty of Computing 
Sri Lanka Institute of information Technology
Malabe, Sri Lanka
MS20911058@my.sliit.lk
	
Abstract – In this paper emphasized that security of Information Technology of public network in aspect of security impact to a client and the resource server which is use art of the technology implementation of this era called Oauth framework 2.0.  This RFC 6749 protocol standard particularly restricted the third party applications through HTTP services without authorization from the respective resource owner.  In fact, it is a challenge of the expertise in this new era due to the complexity of the software industry and as well as aspect of the client requirement. A range of new sophisticated applications further create an uncertainty due to the vulnerabilities and exploitation of the threats unexpectedly. In this review is further illustrated the Oauth framework practically implemented with web applications how could compromised with Google Application Program Interface. 

Key Words: Oauth 2.0 Framework, API, Resource Server, Resource Owner, Client, Authorization Server. Access Token, Authorization Request, Authorization Granted   

I. INTRODUCTION
Information security is based on very primitive but potential important three fundamental principles of security aspects such as confidentiality, integrity, and availability. They are the pillars of the information. Then the challenge would be implementation of the secure systems to prevent or mitigate such intentional misuse of the public or private properties. 

Open Authorization (OAuth) is a protocol which is used to protected the data shared in a public platform such a as Google Drive API. Internet Engineering Task Force has been implemented a framework such as RFC 6749 by defining the standards protocol flow with proper steps of procedures. 

The OAuth framework is illustrated mainly in four different services as following steps:
    • Authorization requested from resource owner and directly granted to the client
    • Sent the granted authorization to authentication server by requesting the token 
    • Issued the token by initializing the granted authorization
    • Client requested the protected resources for the given token
    • Resource server validate the access token, if valid grants the service     

 











Figure 1 OAuth 2.0 Protocol Flow
    A. OAUTH ROLES:
    • Resource Owner
    • Client
    • Resource Server
    • Authorization Server 

    B. ACCESS TOKEN:
Access token is credentials which are access protected resources. It is denoted as unidentified some encrypted date or signature in variable manner. Server can be identified both name and the password in it. Access token basically two formats such as structures and method of utilization whereas cryptographic properties.  
