# Woow_ha_nginxpm — WoowTech Nginx Proxy Manager Home Assistant Add-on Repository

[![Add repository to Home Assistant](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FWOOWTECH%2FWoow_ha_nginxpm)

Home Assistant add-on repository for [Nginx Proxy Manager](https://nginxproxymanager.com/) — a
web-based reverse proxy with automatic Let's Encrypt SSL certificate
management, running as a native Home Assistant add-on.

[Nginx Proxy Manager](https://nginxproxymanager.com/) 的 Home Assistant add-on
倉庫 — 具備網頁管理介面的反向代理，並可自動申請/續約 Let's Encrypt SSL 憑證，
以原生 Home Assistant add-on 形式運行。

## Add-ons in this repository | 本倉庫的 add-on

| Add-on | Description |
|---|---|
| [Woow Nginx Proxy Manager](nginxpm/) | Reverse proxy + Let's Encrypt SSL management with a web UI (amd64/aarch64) |

## Installation | 安裝

1. Click the badge above (or **Settings → Add-ons → Add-on Store → ⋮ →
   Repositories**) and add:
   `https://github.com/WOOWTECH/Woow_ha_nginxpm`
2. Find **Woow Nginx Proxy Manager** in the store and click **INSTALL**.
3. Start the add-on and open the Web UI (port `81`); log in with the default
   credentials `admin@example.com` / `changeme` and change them immediately.
4. Details, options and troubleshooting: [nginxpm/README.md](nginxpm/README.md)

> **Migrated from `Woow_nginxpm_docker_compose_all` (branch `ha`)** — if you
> added the old repository URL, remove it and add this one to keep receiving
> updates. Archived repositories never receive updates.
> 若你先前加入的是舊倉庫網址，請移除並改加本倉庫，才能繼續收到更新；
> 已封存的倉庫不會再發佈新版本。

## Other deployment platforms | 其他部署平台

- Docker/Podman Compose → [Woow_podman_nginxpm](https://github.com/WOOWTECH/Woow_podman_nginxpm)
- K3s/Kubernetes Helm chart → [Woow_k3s_nginxpm](https://github.com/WOOWTECH/Woow_k3s_nginxpm)
