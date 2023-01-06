# xray-vmess-tcp-http
```
# install xray
bash -c "$(curl -L https://github.com/XTLS/Xray-install/raw/main/install-release.sh)" @ install -u root

# copy xray.json to /usr/local/etc/xray/config.json and replace the uuid and port
vim /usr/local/etc/xray/config.json
systemctl restart xray
```
