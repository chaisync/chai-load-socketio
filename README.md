# chai-load-socketio
An load tester for Node Express Socket.io WebSocket Server using Artillery

## Purpose
The purpose of this tester is to apply loads on a Socket.io websocket server.

## Install
1. Global install Artillery on your machine.
```    
    npm install -g artillery
```
2. Verify installation.
```
    artillery dino
```
3. Clone project 
```
    git clone https://github.com/chaisync/chai-load-socketio.git
```

## Run load scripts
1. Run the script in package.json
```
    npm run load
```
2. Run a script by filename
```
    artillery run load_chaisync_12000users_1min.yaml
```


