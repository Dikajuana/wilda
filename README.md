
# UP REPO DEBIAN
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>
# UP REPO UBUNTU
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && reboot</pre></code>

### INSTALL SCRIPT 
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update -y && apt upgrade -y && apt install -y bzip2 gzip coreutils screen curl unzip && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/Dikajuana/wilda/refs/heads/will/setup-main.sh && chmod +x setup-main.sh && sed -i -e 's/\r$//' setup-main.sh && screen -S setupku ./setup-main.sh</code></pre>

### PERINTAH UPDATE 
<pre><code>wget https://raw.githubusercontent.com/Dikajuana/wilda/refs/heads/will/files/update.sh && chmod +x update.sh && ./update.sh</code></pre>

### UNINSTALL SC
<pre><code>wget https://raw.githubusercontent.com/Dikajuana/wilda/refs/heads/will/uninstall.sh && chmod +x uninstall.sh && ./uninstall.sh</code></pre>

### TESTED ON OS 
- UBUNTU 20
- DEBIAN 10 ( Recomended )
### Setup Server
<pre><code>wget https://raw.githubusercontent.com/Dikajuana/wilda/refs/heads/will/setup_vpn_server.sh && chmod +x setup_vpn_server.sh && ./setup_vpn_server.sh</code></pre>

### PORT INFO
```
- TROJAN WS  443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WSS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SSH WS / TLS 443
- SSH NON TLS 8880 80 8080 2082 2095 2086
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```
### Author
```
KCS
```
