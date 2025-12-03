ArrrStack
---------
1. Edit the .env file.
2. Put .env and compose.yaml in the same folder.
3. Run "compose up -d" to launch the stack.
4. Access all services on the IP of the device where they are running and the port. e.g. localipofdevice:8080 for Sabnzbd.
5. done! :)


Services inside compose.yaml
- [Gluetun](https://github.com/qdm12/gluetun) (VPN)
- [Mullvad Browser](https://github.com/mullvad/mullvad-browser)
- [Sabnzbd](https://github.com/sabnzbd/sabnzbd) (.nzb Downloader)
- [Jellyseerr](https://github.com/seerr-team/seerr) (request Movies/Series)
- [Sonarr](https://github.com/Sonarr/Sonarr) (Series organizer)
- [Radarr](https://github.com/Radarr/Radarr) (Movie organizer)
- [Prowlarr](https://github.com/Prowlarr/Prowlarr) (Usenet & Torrent Indexer Manager)
- [Jellyfin](https://github.com/jellyfin/jellyfin) (Media Streaming Software)
