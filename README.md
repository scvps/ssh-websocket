SSH OVER WEBSOCKET ONLY

# Command Install
Copy this code & paste in your vps terminal

```
apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/scvps/ssh-websocket/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
```

Work fine in 
Debian 9 & 10
Ubuntu 18.04 & 20.04

------------------------------------------------------------

   > Service & Port
   - OpenSSH                 : 22
   - SSH Websocket           : 80 [ON]
   - OpenVPN                 : TCP 1194, UDP 2200, SSL 442
   - Stunnel4                : 443, 777
   - Dropbear                : 109, 143
   - Squid Proxy             : 3128, 8080 (limit to IP Server)
   - Badvpn                  : 7100 - 7300
   - Nginx                   : 81

------------------------------------------------------------