# x-ui english version

![инглиш мазафака ду ю спик ит](https://user-images.githubusercontent.com/2741725/158698488-cd7538a8-9bc5-4c11-b60a-6dc18244635f.jpg)

xray panel with multi-protocol multi-user support

# Features
- System status monitoring
- Support multi-user multi-protocol, web page visualization operation
- Supported protocols: vmess, vless, trojan, shadowsocks, dokodemo-door, socks, http
- Support to configure more transmission configurations
- Traffic statistics, limit traffic, limit expiration time
- Customizable xray configuration templates
- Support https access panel (bring your own domain name + ssl certificate)
- For more advanced configuration items, see the panel for details


# Build

```
git clone https://github.com/NixDeveeloper/x-ui-english
cd x-ui-english
go build main.go
mv main /usr/local/bin/x-ui
```

¯\_(ツ)_/¯ 

```
bash <(curl -Ls https://raw.githubusercontent.com/NixDeveeloper/x-ui-english/master/install.sh)
```

```
cd /root/
rm x-ui/ /usr/local/x-ui/ /usr/bin/x-ui -rf
tar zxvf x-ui-linux-amd64.tar.gz
chmod +x x-ui/x-ui x-ui/bin/xray-linux-* x-ui/x-ui.sh
cp x-ui/x-ui.sh /usr/bin/x-ui
cp -f x-ui/x-ui.service /etc/systemd/system/
mv x-ui/ /usr/local/
systemctl daemon-reload
systemctl enable x-ui
systemctl restart x-ui
```

```
Donate Us (Crypto : USDT-TRC20) : TDmwnAGjcookzT3sjhxtR67AQgTDsRiy54
```
