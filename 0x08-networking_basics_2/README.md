0x08. Networking basics #1

 localhost is a hostname that refers to the current computer used to access it. It is used to access the network services that are running on the host via the loopback network interface. Using the loopback interface bypasses any local network interface hardware.

The Internet Protocol Version 4 address 0.0.0.0 can have multiple uses
Official meaning and use
IANA, who allocate IP addresses globally, have allocated the single IP address 0.0.0.0[1] to RFC 1122 section 3.2.1.3. It is named as "This host on this network".

RFC 1122 refers to 0.0.0.0 using the notation {0,0}. It prohibits this as a destination address in IPv4 and only allows it as a source address under specific circumstances.

A host may use 0.0.0.0 as its own source address in IP when it has not yet been assigned an address, such as when sending the initial DHCPDISCOVER packet when using DHCP.

Netcat or nc is a networking utility for debugging and investigating the network.

This utility can be used for creating TCP/UDP connections and investigating them. The biggest use of this utility is in the scripts where we need to deal with TCP/UDP sockets.
