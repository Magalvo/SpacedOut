# Running the Project

## Run with Docker

### 1. Build and Start Everything
```bash
make up
```

This command **builds and starts all services**.

Open in your browser:  
http://localhost:8080

### Useful Commands
```bash
make logs   # Follow container logs
make down   # Stop all containers
```

---

## Run Without Docker

### 1. Start the Frontend
```bash
cd AdAstraPerDuckUa/frontend
npx http-server
```

### 2. Start the Backend
```bash
cd AdAstraPerDuckUa/backend
npx node-gyp rebuild
node server.js
```
