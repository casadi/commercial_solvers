How to renew Gurobi license via VPN?


Pseudo code:
for IP in `nslookup license.gurobi.com`:
  `sudo ip route add <IP>/32 dev tun0`
