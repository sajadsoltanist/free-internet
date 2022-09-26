# free-internet
all you need to run or use to have an internet without no limitation

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
OpenVpn Server Setup:
* [openvpn-install](https://github.com/angristan/openvpn-install) - Simple with one command

* [openvpn-install](https://github.com/hwdsl2/openvpn-install) - OpenVPN Server Auto Setup Script

* [openvpn-install](https://github.com/Nyr/openvpn-install) - Simple with one command

Telegram:
* [MTProxy](https://github.com/TelegramMessenger/MTProxy) - MTProto Proxy with Docker Image
* [mtg](https://github.com/9seconds/mtg) - MTProto Proxy with Docker Image

* [telegram](https://github.com/zhinacode/telegram) - socks5 , SSH between 2 server
