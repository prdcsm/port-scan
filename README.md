Port scanner:
  
  Two types of port scans to be passed as argument in the regular scanner:

   - -r: port range scan - searches a range of ports, example: python3 portscan.py -r 127.0.0.1 20 25
   - -s: specific ports (max 5) - looks for specific ports, example: python3 portscan.py -s 127.0.0.1 22 80 443
