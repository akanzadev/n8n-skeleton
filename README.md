# 📦 n8n Skeleton

Minimal starter template to run and extend [n8n](https://n8n.io/), the open-source workflow automation tool.  
This skeleton is designed to help you quickly set up a self-hosted n8n instance using Docker, with the flexibility to add custom nodes, credentials, or workflows.

---

## 📁 Project Structure

- `.env.example` – Template for environment variables
- `.gitignore` – Standard ignores for Node.js and Docker
- `docker-compose.yml` – Launch n8n using Docker with minimal setup
- `package.json` – Ready to extend with custom packages
- `README.md` – Project documentation and usage guide

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/n8n-skeleton.git
cd n8n-skeleton
```

### 2. Configure Environment

Copy the example environment file and edit it if needed:

```bash
cp .env.example .env
```

### 3. Start n8n with Docker

```bash
docker-compose up -d
```

Once the containers are up, open your browser and go to:

```bash
http://localhost:5678
```

---

## 🛠️ Customization

You can extend this skeleton by:

- Creating custom nodes (via `packages/nodes-base`)
- Adding shared workflows
- Installing npm packages for external integrations
- Setting up volume mounts for persistence

"You may also configure reverse proxies, SSL, or connect to external databases as needed."

## 🧩 Dependencies

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [n8n](https://n8n.io/)

## 🙌 Credits

Built with ❤️ using [n8n](https://n8n.io/)

## 📄 License

[MIT License](LICENSE)
