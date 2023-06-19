# Muon-NODE
INSTALL MANUAL MUON_NODE
### Update apt klik perintah berikut
```
sudo apt-get update
```

### Install NPM
```
sudo apt install npm
```

### Install Git
```
sudo apt install git-all
```

### Install Docker.io 
```
sudo apt install docker.io
```

### Install Docker Compose 
```
sudo apt install docker-compose
```

### Clone Github
```
git clone https://github.com/muon-protocol/muon-node-js.git --recurse-submodules --branch testnet
```

### run Muon node 
```
cd muon-node-js
```

### Run Docker 
```
docker-compose build
```

### Run NPM
```
npm install
```
```
npm i -g pm2
```

### Start Muon Node compose 
```
docker-compose up -d
```

### Backup file pharase ke metamask jangan sampai hilang.
```
cd ~/muon-node-js
docker exec -it muon-node ./node_modules/.bin/ts-node ./src/cmd keys backup > backup.json
```

### klik perintah berikut untuk memunculkan privat key dan impor privat key ke wallet metamask.
```
cat backup.json
```

### Next buka https://alice.muon.net/join/ connect dengan wallet metamask jaringan BSC testnet,, request faucet BSC testnet.
