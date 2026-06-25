**TCP/IP (Transmission Control Protocol/Internet Protocol)**

- TCP/IP is a protocol suite used for communication between devices.
- It is a practical model (OSI is a theoretical model).
- TCP/IP provides rules for
  - Sending data
  - Receiving data
  - Addressing devices
  - Routing packets.
- 4 Layers:
  - Application Layer  --> Combines Application, Presentation and Session Layers of OSI Model
  - Transport Layer  --> Tranasport Layer of OSI Model
  - Internet Layer  --> Network Layer of OSI Model
  - Network Access Layer  --> Combines Data Link and Physical Layers Of OSI Model.


| Layer No. | Layer Name     | Main Functions                                                                                    | Protocols                 |
| --------- | -------------- | ------------------------------------------------------------------------------------------------- | -------------------------------- |
| 4         | Application    | - Provides services to user applications<br> - Data representation<br> - Process-to-process communication <br> - Closest to the user | HTTP, HTTPS, FTP, SMTP, DNS, SSH |
| 3         | Transport      | - End-to-end communication<br> - Segmentation<br> - Flow Control<br> - Error Checking                | TCP, UDP                         |
| 2         | Internet       | - Logical addressing<br> - Routing packets between networks                                            | IP, ICMP, ARP                    |
| 1         | Network Access | - Physical transmission of data<br> - MAC addressing<br> - Framing (converts packets to frames)                                       | Ethernet, Wi-Fi, PPP             |
