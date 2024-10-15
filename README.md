# Wireguard-UI
Wireguard VPN with web-interface.

## Usage:
- Enable IPv4 Forwarding:
```bash
sudo sysctl -w net.ipv4.ip_forward=1
```
- Set or delete env variables
```
WGUI_ENDPOINT_ADDRESS
TELEGRAM_TOKEN
```

- Build and Start Docker containers
```bash
docker compose up --build -d
```
- Web-interface on http://host:5000

## Info
- Meta IPs in Extra Allowed IPs
- For LAN-access set `WGUI_DNS` and `WGUI_DEFAULT_CLIENT_ALLOWED_IPS`

## Official repo and docs
https://github.com/ngoduykhanh/wireguard-ui
