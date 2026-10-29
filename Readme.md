**OSI / TCP-IP Network Simulator** Speed

Select mode: drag devices; click a cable to bring it down/up. Link mode: click two devices. Orange dot = one frame on the wire (visual abstraction).

Tutorial · limits

1\) Pick scenario D. 2) Select PC1 → Send ping to PC2’s IP. 3) Press Step repeatedly: ARP request is broadcast, switch learns MACs, router does longest-prefix match and TTL−1, then new MACs on the far LAN. 4) Click any event, open the Packet tab: highlighted rows are fields that changed since the previous hop (MACs, TTL) while IP src/dst stay. Build your own: +PC/+Switch/+Router, Link mode, then set IPs in the Device tab.

**Educational simulation, not a real emulator.** Not implemented: DNS/HTTP, DHCP, VLANs, NAT, hubs/collisions, wireless, TCP retransmission/windowing (fields shown, values fixed), ICMP error messages, MAC aging, fragmentation. TCP/UDP use fixed ports (TCP 80, UDP 5000). Presentation/Session layers have no real headers here and are explained rather than simulated.