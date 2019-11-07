# multi_psiphon
run multiple psiphon to increase performance 

This works on linux-amd64
clone the repository 
note that the configuration .text files are configured to use FRONTED-MEEK-OSSH

```
apt install haproxy -y

cd multi_psiphon

chmod +x pslnx 
chmod +x startpslnx.sh

./startpslnx.sh
```

then configure your browser to socks5 proxy 127.0.0.1 port 7777
or you can install redsocks and forward all traffic to 7777 using iptables 
