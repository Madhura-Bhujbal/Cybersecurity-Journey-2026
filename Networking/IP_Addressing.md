**IP (Internet Protocol)**

- An IP Address is a unique logical address assigned to a device in a network.
- It is used to identify devices in a network and enable communication between them.

1) IPv4
2) IPv6

**Difference Between IPv4 and IPv6**

| Feature                | IPv4                          | IPv6                                                   |
| ---------------------- | ----------------------------- | ------------------------------------------------------ |
| Length         | 32 bits                       | 128 bits                                               |
| Notation        | Dotted Decimal (e.g., 192.168.1.1)   | Hexadecimal (e.g., 2001:db8::1)                        |
| Address Representation | Four octets separated by dots | Eight hextets (groups of hexadecimal digits) separated by colons |
| Size of each group | 8 bits | 16 bits |
| Range of each octet | 0 - 255 | 0000- ffff(0 - 9 / a-f) |
| Header Size            | Variable (20–60 bytes)        | Fixed (40 bytes)                                       |
| Address Configuration  | Manual or DHCP                | Auto-configuration (SLAAC) and DHCPv6                  |
| Security               | IPsec is optional             | IPsec support is built into the protocol suite         |
| Broadcast              | Supports broadcast            | No broadcast; uses multicast and anycast               |
| NAT                    | Commonly used                 | Generally not required due to the large address space  |
| Example                | 192.168.1.10                  | 2001:0db8:85a3:0000:0000:8a2e:0370:7334                |


Classes Of IPv4:
| Class | Range | Default Subnet Mask | Purpose |
|-------|-------|---------------------|---------|
| Class A | 1.0.0.0 – 126.255.255.255 | 255.0.0.0 (/8) | Large Networks |
| Class B | 128.0.0.0 – 191.255.255.255 | 255.255.0.0 (/16) | Medium Networks |
| Class C | 192.0.0.0 – 223.255.255.255 | 255.255.255.0 (/24) | Small Networks |
| Class D | 224.0.0.0 – 239.255.255.255 | N/A | Multicasting |
| Class E | 240.0.0.0 – 255.255.255.255 | N/A | Experimental |
