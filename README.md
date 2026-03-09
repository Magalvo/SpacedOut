## Run with Docker
1. ==========================
make up (builds + starts everything)
Open http://localhost:8080

INFO. ==========================
make logs -> to follow logs
make down -> to stop

# OR 


## Run without Dockerino 
1. =========================
cd AdAstraPerDuckUa\frontend
npx http-server

2. =========================
cd AdAstraPerDuckUa\backend
npx node-gyp rebuild
node server.js