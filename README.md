***P i n g P o n g***

PingPong is a simple multi-host ping tool.
- Simultaneous ping to  multi hosts
- Each host can be in one of two modes:
  - ICMP (ICMP Echo Request)
  - TCP (Full Syn -> SynAck -> Ack handshake, and Fin -> Ack teardown;  Equivalent to nmap "TCP connect scan" (-sT))
- Save/load host list to/from CSV
