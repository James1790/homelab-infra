# Network Overview (In Progress)

```mermaid
graph TD
    Internet --> Router
    Router --> Switch
    Switch --> Server[Ubuntu Server]
    Server --> Docker[Docker Engine]
    Docker --> Jellyfin
    Docker --> Radarr
    Docker --> Sonarr
    Docker --> SABnzbd
    Docker --> piHole
    Docker --> TailScale
