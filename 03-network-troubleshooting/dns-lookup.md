# DNS Lookup Test

## Purpose
Verify that the client can reach the DNS server and resolve domain names to IP addresses.

## Commands Executed
- `nslookup mydomain.com`
- `ipconfig /all`

## Results
- The DNS server responded and returned both IPv6 and IPv4 addresses.  
- The client received the IP address `172.16.0.100` and DNS suffix `mydomain.com`.

## Evidence
<p align="left">
  <img width="600" alt="DNS Lookup Screenshot" src="https://github.com/user-attachments/assets/6e438b2e-26fa-4e4b-88fc-abab4ae7ef20" />
</p>

*Figure 1 – DNS Lookup and IP configuration results.*

