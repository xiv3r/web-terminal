# TTYD

<img src="https://github.com/xiv3r/web-terminal/blob/main/bin/ttyd.png">

# Installation

- For openwrt
```
opkg install luci-app-ttyd
```
- For amd64
```
sudo apt install ttyd
```
- For aarch64
```
wget -O /bin/ttyd https://raw.githubusercontent.com/xiv3r/web-terminal/refs/heads/main/bin/ttyd-aarch64 && chmod 700 /bin/ttyd && ttyd -p 8080 bash &>/dev/null & pid=$!
```

- For arm64
```
wget -O /bin/ttyd https://raw.githubusercontent.com/xiv3r/web-terminal/refs/heads/main/bin/ttyd-arm64 && chmod 700 /bin/ttyd && ttyd -p 8080 bash &>/dev/null & pid=$!
```

- For armhf
```
wget -O /bin/ttyd https://raw.githubusercontent.com/xiv3r/web-terminal/refs/heads/main/bin/ttyd-armhf && chmod 700 /bin/ttyd && ttyd -p 8080 bash &>/dev/null & pid=$!
```
# Run
```
ttyd -p 8080 bash &>/dev/null & pid=$!
```
Open the Browser 👉 [http://localhost:8080](http://localhost:8080)


<br>
<br>
<br>
Binaries Credits: [tsl0922](https://github.com/tsl0922/ttyd)
