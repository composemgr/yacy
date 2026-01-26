## 👋 Welcome to yacy 🚀

Decentralized peer-to-peer web search engine

## 📋 Description

Decentralized peer-to-peer web search engine

## 🚀 Services

- **yacy**: yacy/yacy_search_server:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/yacy/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/yacy" ~/.local/srv/docker/yacy
cd ~/.local/srv/docker/yacy
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install yacy
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8084

## 📂 Volumes

- `./rootfs/config/yacy` - Data storage
- `./rootfs/data/yacy` - Data storage

## 🔍 Logging

```shell
docker compose logs -f yacy
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
