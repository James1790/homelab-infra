# Network Overview (In Progress)

This diagram represents the current layout of my homelab environment, including the Ubuntu Server host, Docker Engine, and the containerized services running on it.



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
