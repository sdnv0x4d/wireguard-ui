# Wireguard-UI
Wireguard VPN with web-interface.

## Usage:
- Enable IPv4 Forwarding:
```bash
sudo sysctl -w net.ipv4.ip_forward=1
```
- Build and Start Docker containers
```bash
docker compose up --build -d
```
- Web-interface on http://host:5000

## Official repo and docs
https://github.com/ngoduykhanh/wireguard-ui
