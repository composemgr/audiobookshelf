# Audiobookshelf

A self-hosted application for managing audiobookshelf.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/audiobookshelf/main/docker-compose.yaml" | docker compose -f - up -d
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

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
