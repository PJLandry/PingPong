**P i n g P o n g**

PingPong is a simple multi-host ping tool.
- Simultaneous ping to  multi hosts
- Each host can be in one of two modes:
  - ICMP (ICMP Echo Request)
  - TCP (Full Syn -> SynAck -> Ack handshake, and Fin -> Ack teardown;  Equivalent to nmap "TCP connect scan" (-sT))
- Save/load host list to/from CSV

On Windows: Download and run the setup.exe file.

On Linux:  Download, install and run the flatpack file.   
Note: If your distribution won't let you do an ICMP ping without sudo, use this command to allow it (will not persist reboots): *sudo sysctl -w net.ipv4.ping_group_range="0 2147483647"*

