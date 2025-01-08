![logo]((https://github.com/allwinrajan/OSI-REFERENCE-MODEL/blob/750b32c69ab81d30b13a2e1f270d4df38bf98631/Layering%20Diagram.png))

# OSI REFERENCE MODEL

### Layer 1: Physical Layer 
- Responsible for actual physical connection among the devices. 
- This Layer contain information in the form of bits. 
Layer 1 devices: Hub, Modem, Repeater and cables 



### Layer 2: Data Link Layer 
- Its responsible for node-to-node delivery of message. 
- The main function of this layer 2 is make sure the data is secure and error free from one node to another, over the physical layer. 
- The data link layer divided into two sub layers  
1. LLC (Logical Link Control) 
2. MAC (Media Access Control) 
- DLL is Also encapsulating the Sender’s and Receiver’s MAC Address in the header 
Layer 2 Devices: Switches, Bridges 



### Layer 3: Network Layer 
- It works for transmission for data from one host to another, and it take care of packet routing i.e. finds shortest path for data transmission over available route. 
Layer 3 Devices: Switches, Routers 



### Layer 4: Transport Layer 
- Transport layer is taking the service from network layer, provide the service to the application layer 
- The data in the transport layer is called segments 
- Its responsible for end-to-end data transmission and acknowledge the successful data transfer 
Protocols Used in Layer 4: TCP, UDP 



### Layer 5: Session Layer 
- Session layer responsible for establish the session, manage the session and terminate the session between two devices. 
Protocols Used in Layer 5: NetBIOS, PPTP 



### Layer 6: Presentation Layer 
- The data from application layer is extracted here and manipulate the data as per the required format 
Protocols Used in Layer 6:  JPEG, MPEG 



### Layer 7: Application Layer 
- The layer which is close to the end user, this layer serves a window for application service to access the network resources and displaying it to  
 end-user.  

Protocols Used in Layer 6: SMTP, DNS, FTP 

