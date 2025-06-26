# Module Federation

### Installation

```bash
# Clone the repository
git clone https://github.com/vitorlsouza/mf-app.git
cd mf-app

# Install dependencies
pnpm install

# Start development servers
pnpm dev
```

### 🌐 Access the Applications

- **Host**: http://localhost:8080
- **Remote**: http://localhost:8081

## 📋 Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start both applications in development mode |
| `pnpm build` | Build both applications for production |
| `pnpm run host:dev` | Start only the host application |
| `pnpm run remote:dev` | Start only the remote application |

## 🏗️ Architecture

```
Host App (8080) ←→ Remote Module (8081)
     ↓                    ↓
  Container           Exposed App
  Component           Component
```

## 📁 Project Structure

```
mf-app/
├── 📂 host/                    # Main application
│   ├── 📂 src/
│   │   ├── App.tsx            # Host main component
│   │   ├── index.ts           # Entry point
│   │   └── index.css          # Global styles
│   ├── module-federation.config.ts
│   ├── rspack.config.ts
│   └── package.json
│
├── 📂 remote/                  # Remote module
│   ├── 📂 src/
│   │   ├── App.tsx            # Exposed component
│   │   ├── index.ts           # Entry point
│   │   └── index.css          # Module styles
│   ├── module-federation.config.ts
│   ├── rspack.config.ts
│   └── package.json
│
└── package.json               # Root configuration
```

## 🔧 Development

### Default Ports
- **Host**: http://localhost:8080
- **Remote**: http://localhost:8081
