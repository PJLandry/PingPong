**P i n g P o n g**

PingPong is a simple multi-host ping tool.
- Simultaneous ping to  multi hosts
- Each host can be in one of two modes:
  - ICMP (ICMP Echo Request)
  - TCP (Full Syn -> SynAck -> Ack handshake, and Fin -> Ack teardown;  Equivalent to nmap "TCP connect scan" (-sT))
- Save/load host list to/from CSV

On Windows: Download the dist.zip archive, it contains the required QT runtime files.  Download pingpong.exe and place it in the same folder as the contents of the dist.zip file (overwrite the old pingpong.exe)

On Linux:  Download, install and run the flatpack file.   If your distribution won't let you do an ICMP ping without sudo, use this command to allow it (will not persist reboots): *sudo sysctl -w net.ipv4.ping_group_range="0 2147483647"*

