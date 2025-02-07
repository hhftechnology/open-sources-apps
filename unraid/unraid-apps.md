# Unraid Community Apps

### Media Management
[Plex](https://plex.tv) - Advanced media server for your photos, movies, shows, and music. `media,streaming,transcoding` `CA:yes` `docker:[plexinc/pms-docker]`
[Jellyfin](https://jellyfin.org) - Open source media streaming solution. `media,streaming,opensource` `CA:yes` `docker:[jellyfin/jellyfin]`
[Emby](https://emby.media) - Media server for personal streaming. `media,streaming,transcoding` `CA:yes` `docker:[emby/embyserver]`

### Download Management
[SABnzbd](https://sabnzbd.org) - Easy-to-use binary newsreader. `usenet,download` `CA:yes` `docker:[linuxserver/sabnzbd]`
[qBittorrent](https://www.qbittorrent.org) - Open-source BitTorrent client. `torrent,download` `CA:yes` `docker:[linuxserver/qbittorrent]`

### Backup Solutions
[Duplicati](https://www.duplicati.com) - Backup software with encryption. `backup,encryption` `CA:yes` `docker:[linuxserver/duplicati]`
[Restic](https://restic.net) - Fast and secure backup solution. `backup,encryption,cli` `CA:yes`

### System Monitoring
[Grafana](https://grafana.com) - Analytics and monitoring solution. `monitoring,dashboard,metrics` `CA:yes` `docker:[grafana/grafana]`
[Prometheus](https://prometheus.io) - Monitoring system and time series database. `monitoring,metrics` `CA:yes` `docker:[prom/prometheus]`

### Network Management
[Nginx Proxy Manager](https://nginxproxymanager.com) - Reverse proxy with SSL management. `proxy,networking,ssl` `CA:yes` `docker:[jc21/nginx-proxy-manager]`
[Tailscale](https://tailscale.com) - Zero config VPN solution. `vpn,networking` `CA:yes` `docker:[tailscale/tailscale]`
