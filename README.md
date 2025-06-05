## Projects
**Project 2**: Network Traffic Analysis with Wireshark. 
  
## Setup Instructions

**Project: Network Traffic Analysis with Wireshark.**

1. Downloaded and Installed Wireshark on Ubuntu Machine. 

2. Selected Network interface to capture traffic. 

3. Captured Network traffic on enp0s3 by visiting websites to generate HTTP/HTTPS taffic.
   
![Screenshot 2025-06-04 224948](https://github.com/user-attachments/assets/c99dda50-4359-4ee2-bfe2-d76883357dbc)


4. Analyze Network Traffic by filtering with the following filters - TCP, HTTP, Ip.Addr= 104.22.10.26 ( for specific IP address).

   
![filtered by specific IP address](https://github.com/user-attachments/assets/7c07f013-0628-4bdc-b78a-5ec1f8113481)


![filtered by tcp](https://github.com/user-attachments/assets/fb8db74d-f1d9-4034-be98-f278823d27b1)



5. Followed TCP streams by right clicking and chosing TCP to see the entire conversation.

![tcp streams](https://github.com/user-attachments/assets/4c4ba74b-534b-4fa5-9483-5076cb0297a8)



6.Inspected packet contents by expanding the packet details to inspect the headers and payload of each layer ( Ethernet, IP, TCP, etc).



## Tools Used
Ubuntu Virtual Machine, Wireshark.
