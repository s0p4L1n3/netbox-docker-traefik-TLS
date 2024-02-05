# netbox-docker-traefik-TLS
Netbox docker with Traefik and Self Signed Cert

Netbox version 3.7.2-2.8.0
Traefik vesion 2.11

1. Download this project
2. Generate your own netbox TLS/private key pair.
3. Copy paste content on secret/
4. Rename the netbox.lab.lan-crt.pem & netbox.lab.lan-key.pem according to your netbox fqdn.
5. Edit docker-compose.yml & traefik/config.yml according to the rename.
7. Create a DNS Record on your LAN pointing to your docker host IP.
8. docker compose up -d
