# Homelab Infrastructure Engineering Project (In Progress)
This homelab is an ongoing project designed to mirror real data center and cloud infrastructure environments. It currently includes a full media automation stack running on Ubuntu Server using Docker, persistent storage, and basic system hardening. The goal is to continue expanding this environment into a more complete platform that demonstrates my experience with Linux, container orchestration, networking, and secure remote access.

## Current Features
### Media Automation Stack
The following services are deployed using Docker Compose:
- Jellyfin - Media Server
- Radarr - Movie Info Automation
- Sonarr - TV Info Automation
- SABnzbd - Usenet Downloader
- qBittorrent - Torrent Client
- Supporting containers (as needed)

### What's implemented today
- Docker Compose deployment
- Persistent storage using bind mounts
- Basic container networking
- Service health checks
- Linux server setup (Ubuntu)
- Secure remote access
- System Monitoring
- Working ingest to deployment media workflow
This reflects the same troubleshooting and container workflows I have used while supporting hyperscale compute clusters.

## Planned Additions
These are the next steps I will be adding to the project:

### Short-term roadmap
- Add a simple network diagram
- Add a storage layout overview
- Add documentation for each service
- Add a troubleshooting section for common issues

### Long-term roadmap
- Expand into Kubernetes (K3s or MicroK8s)
- Add centralized logging
- Add Prometheus + Grafana monitoring
- Add local AI inference services
- Add automated backups and snapshots

This repo will grow as I continue rebuilding and improving my homelab!
