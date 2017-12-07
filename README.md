# pysec
python scripts for penetration testing

Port scanners:
  - regular: portscan.py
  - interactive: portscan_interactive.py
  
  Two types of port scans:
   - -r: port range scan - searches a range of ports, example: python3 portscan.py -r 127.0.0.1 20 25
   - -s: specific port range (max 5) - looks for specific ports, example: python3 portscan.py -s 127.0.0.1 22 80 443
