# My Network Report (phone hotspot)

## Problem
I wanted to understand how my network works and how to check it with basic commands.

## Steps
- **ping google.com:** ping checks whether I can reach google.com and measures the round-trip time. My result was 0% packet loss and an average of 42 ms.
- **nslookup google.com:** nslookup asks a DNS server for the IP addresses behind a name. For google.com it returned several IPv4 and IPv6 addresses.
- **tracert google.com:** tracert showed the route from my laptop to google.com in 5 hops, starting with my phone. Two hops timed out, which is normal because some routers ignore these packets.
