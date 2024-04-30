---
{"dg-publish":true,"permalink":"/code/ssh-tunneling/","tags":["tutorial"]}
---


[Here](https://docs.hostdime.com/hd/security/browsing-the-internet-through-an-ssh-tunnel-on-macos) a tutorial.

Keys aspects:

- Run this command
```
ssh -f -N -M -S /tmp/sshtunnel -D 1080 USER@server.domain.com -p22
```

In my case I use Digital Ocean so I do
```
ssh -f -N -M -S /tmp/sshtunnel -D 1080 root@138.68.5.73 -p22
```

Then, on MacOS go to Network -> Proxies -> 
SOCKS and create a new server with the ip `127.0.0.1` and port `1080`