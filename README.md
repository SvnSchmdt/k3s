# 🧩 K3s Cluster Setup

This repository contains my personal setup for a lightweight [K3s](https://k3s.io/) Kubernetes cluster — perfect for self-hosted apps, homelabs, and small-scale production environments.

## 🚀 Features

- 🐳 **K3s**: Minimal, single/multi-node Kubernetes cluster
- 🌐 **Traefik**: Built-in reverse proxy and ingress controller
- 🔐 **Cloudflare Tunnel**: Public access through CGNAT/dynamic IP (great for home networks)
- 🔒 **cert-manager**: Automated TLS certificate management via Let's Encrypt
- 📦 **Helm**: Easy application deployment using Helm charts
- 🛡️ **Cloudflare DNS**: Automatic DNS record updates & secure HTTPS integration

## 📁 Project Structure

```bash
k3s-cluster/
│
├── manifests/            # Kubernetes manifests for apps & services
├── helm-charts/          # Custom or modified Helm charts
├── scripts/              # Automation and maintenance scripts
├── traefik/              # Traefik config incl. TLS, middlewares, routers
├── cloudflare/           # Cloudflare Tunnel and DNS configs
```

## ⚙️ Requirements

- Linux server or VM
- Docker or containerd
- Access to Cloudflare API (for DNS & tunnel)
- `kubectl`, `helm`, and optionally `k9s`

## 📦 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/k3s-cluster.git
   cd k3s-cluster
   ```

2. Run setup scripts or follow individual setup guides in each folder.

3. Customize the configuration files to match your domain, Cloudflare API key, and app settings.

## 📄 License

MIT License. Feel free to use and adapt!
