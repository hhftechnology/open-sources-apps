# Unraid Community Apps Collection

A curated list of recommended applications for Unraid servers, including official and community reviews.

## Categories

### Media Management

[Plex](https://plex.tv) - Advanced media server for your photos, movies, shows, and music. `media,streaming,transcoding` `CA:yes` `docker:plexinc/pms-docker` `MIT`
- **Official Review**: Excellent media server with robust transcoding capabilities. Well-integrated with Unraid and easy to set up. Hardware transcoding requires Plex Pass.
- **Resources**: [Support](https://support.plex.tv) [Docker Hub](https://hub.docker.com/r/plexinc/pms-docker)

[Jellyfin](https://jellyfin.org) - Open source media streaming solution. `media,streaming,opensource` `CA:yes` `docker:jellyfin/jellyfin` `GPL-2.0`
- **Official Review**: Excellent free alternative to Plex. Full feature set without subscription. Great Unraid compatibility.
- **Resources**: [Documentation](https://jellyfin.org/docs/) [GitHub](https://github.com/jellyfin/jellyfin)


### Download Management

[SABnzbd](https://sabnzbd.org) - Easy-to-use binary newsreader. `usenet,download` `CA:yes` `docker:linuxserver/sabnzbd` `GPL-2.0` `rating:4.8`
- **Official Review**: Best Usenet downloader available. Excellent integration with media managers.
- **Resources**: [Wiki](https://sabnzbd.org/wiki/) [GitHub](https://github.com/sabnzbd/sabnzbd)

### Backup Solutions

[Duplicati](https://www.duplicati.com) - Backup software with encryption. `backup,encryption` `CA:yes` `docker:linuxserver/duplicati` `LGPL-2.1`
- **Official Review**: Strong encryption and cloud support. Some stability issues reported.
- **Resources**: [Documentation](https://duplicati.readthedocs.io/) [GitHub](https://github.com/duplicati/duplicati)

### System Monitoring

[Grafana](https://grafana.com) - Analytics and monitoring solution. `monitoring,visualization` `CA:yes` `docker:grafana/grafana` `AGPL-3.0`
- **Official Review**: Professional-grade monitoring. Excellent with Prometheus for Unraid stats.
- **Resources**: [Docs](https://grafana.com/docs/) [Community](https://community.grafana.com)

### Network Management

[Nginx Proxy Manager](https://nginxproxymanager.com) - Easy proxy host management. `proxy,networking` `CA:yes` `docker:jc21/nginx-proxy-manager` `MIT`
- **Official Review**: Essential tool for reverse proxy management. User-friendly interface.
- **Resources**: [Documentation](https://nginxproxymanager.com/guide/) [GitHub](https://github.com/NginxProxyManager/nginx-proxy-manager)  