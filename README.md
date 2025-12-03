ArrrStack
---------
1. Edit the .env file.
2. Put .env and compose.yaml in the same folder.
3. Run "compose up -d" to launch the stack.
4. Access all services on the IP of the device where they are running and the port. e.g. localipofdevice:8080 for Sabnzbd.
5. done! :)


Services inside compose.yaml
- Gluetun (VPN)
- Mullvad Browser
- Sabnzbd (.nzb Downloader)
- Jellyseerr (request Movies/Series)
- Sonarr (Series organizer)
- [Radarr](https://github.com/Radarr/Radarr) (Movie organizer)
- Prowlarr (Usenet & Torrent Indexer Manager)
- Jellyfin (Media Streaming Software)
