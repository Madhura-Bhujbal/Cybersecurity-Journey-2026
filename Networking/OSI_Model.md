**OSI (Open Systems Interconnection)**

- It explains how data flows from one device to another device in a network.
- It is a conceptual framework that divides communication into 7 layers, where each layer has a specific responsibility.
- It standardizes communication and simplifies troubleshooting.
- The 7 layers are as follows:
   - Application Layer
   - Presentation Layer
   - Session Layer
   - Transport Layer
   - Network Layer
   - Data Link Layer
   - Physical Layer


| Layer No. | Layer Name | Main Functions | Common Protocols |
|------------|------------|----------------|------------------|
| 7 | Application |<ul><li>Provides network services to end users and applications.<li>Closest to the user.</ul> | HTTP,(80) HTTPS(443), FTP(20,21), SMTP(25), DNS(53) |
| 6 | Presentation |<ul><li>It is also called as Translation Layer.<li>Functions:<br> - Encryption <br> - Decryption<br> - Format Conversion<br> - Compression</ul> | SSL/TLS |
| 5 | Session | Establishes, manages, and terminates sessions | NetBIOS, RPC |
| 4 | Transport |<ul><li>Provides End-to-end communication,<li>Functions:<br> - Segmentation<br> - Flow control<br> - Error checking | TCP(Transmission Control Protocol), UDP(User Datagram Protocol) |
| 3 | Network |<ul><li>Functions:<br> - Routing packets between network.<br> -Determines the best path to destination.<br> - Logical Addressing <li> Addressing : IP Addressing. <li> Device : Router   | IPv4, IPv6 |
| 2 | Data Link |<ul> <li> Framing, MAC addressing, error detection.<li> Addressing : MAC Addressing. <li> Device : Switch | Ethernet, PPP, Switch Protocols |
| 1 | Physical | <ul> <li>Transmission of raw bits over physical media<br>  <li> Devices : Hub | Ethernet Cable, Fiber Optics, Wi-Fi Signals |

Imp concepts:
1) **ENCAPSULATION:**
   
   Process in which each layer addds its own header(i.e information) before transmitting data.
   - Data
   - TCP Header + Data
   - IP Header + TCP Header + Data
   - MAC Header + IP Header + TCP Header + Data


2) **DECAPSULATION:**
   
   Receiver removes the header layer by layer
