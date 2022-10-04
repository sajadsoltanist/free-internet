# free-internet
![image](https://github.com/sajadsoltanist/free-internet/blob/main/internet-freedom.jpg)
### all you need to run or use to have an internet without no limitation
### feel free to make a pull request
### port forwarding tunneling with iptables:
```bash
iptables -t nat -A PREROUTING -p tcp --dport PORT -j DNAT --to-destination IP:PORT
iptables -t nat -A PREROUTING -p udp --dport PORT -j DNAT --to-destination IP:PORT
iptables -t nat -A POSTROUTING -j MASQUERADE
```
### SSH Tunneling:
```bash
ssh -o GatewayPorts=true  -N -L YOURPORT:0.0.0.0:destinationPORT USER@IP
```
# VPN Clients:
### Windows:
* [netch](https://github.com/netchx/netch/releases) - netch windows
* [sstap](https://github.com/githello123/sstap) - sstap (shadowsocks only)
* [outline](https://github.com/Jigsaw-Code/outline-client/releases) - outline (shadowsocks only)


# VPN Servers:
OpenVpn Server Setup:
* [openvpn-install](https://github.com/angristan/openvpn-install) - Simple with one command

* [openvpn-install](https://github.com/hwdsl2/openvpn-install) - OpenVPN Server Auto Setup Script

* [openvpn-install](https://github.com/Nyr/openvpn-install) - Simple with one command
### Wireguard
* [Wireguard](https://www.wireguard.com/quickstart/) - official wireguard guide
### shadowsocks
* [shadowsocks](https://shadowsocks.org/guide/what-is-shadowsocks.html) - official shadowsocks guide
### Vmess:
* [V2Fly](https://www.v2fly.org/en_US/) - Vmess Server, Client guide
### Telegram:
* [MTProxy](https://github.com/TelegramMessenger/MTProxy) - MTProto Proxy with Docker Image
* [mtg](https://github.com/9seconds/mtg) - MTProto Proxy with Docker Image

* [telegram](https://github.com/zhinacode/telegram) - socks5 , SSH between 2 server


### Tutorials
* [shadowsocks-obfs](https://youtu.be/rtGPtn0Fkv8) - shadowsocks-obfs
* [V2ray](https://youtu.be/Nzc0VXzJe8Y) - V2ray ( Persian )
