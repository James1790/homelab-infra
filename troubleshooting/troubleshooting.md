# Troubleshooting Guide

This document covers common issues in the homelab environment and the steps used to diagnose and resolve them.

---

## Container Issues
### Symptoms
- Container not starting
- Permission errors
- Missing volumes

### Commands
- docker compose logs <service>
- docker ps -a
- docker inspect <service>

### Fixes
- Correct volume paths
- Ensure PUID/PGID match host user
- Recreate container after config changes

---

## Network Issues
### Symptoms
- Services unreachable
- DNS failures
- Slow downloads

### Commands
- ping
- nslookup
- ip a
- docker network inspect

### Fixes
- Restart Docker
- Rebuild Docker network
- Validate router/firewall rules

---

## Storage Issues
### Symptoms
- Media not importing
- Permission denied
- Disk full

### Commands
- df -h
- ls -l
- journalctl -xe

### Fixes
- Correct mount points
- Fix permissions
- Expand storage
