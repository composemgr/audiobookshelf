## 👋 Welcome to audiobookshelf 🚀

Self-hosted audiobook and podcast server

## 📋 Description

Self-hosted audiobook and podcast server

## 🚀 Services

- **audiobookshelf**: linuxserver/audiobookshelf:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/audiobookshelf/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/audiobookshelf" ~/.local/srv/docker/audiobookshelf
cd ~/.local/srv/docker/audiobookshelf
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install audiobookshelf
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
SERVICE_USER=1000
SERVICE_GROUP=1000
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:13378

## 📂 Volumes

- `./rootfs/config/audiobookshelf` - Data storage
- `./rootfs/data/audiobookshelf` - Data storage
- `./rootfs/data/media` - Data storage
- `./rootfs/data/downloads` - Data storage

## 🔍 Logging

```shell
docker compose logs -f audiobookshelf
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
