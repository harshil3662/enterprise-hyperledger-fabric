Hyperledger Fabric Fishing Sample App

Prerequisite:

- Set up Ubuntu on VirtualBox with Vagrant (recommended Ubuntu v16.04 LTS)
- Set up Docker, Docker-Compose
- Install Golang
- Install Node, npm

Blockchain Network:

- Go to network folder and run script for network configuration:

     vagrant@vagrant: ./generate.sh

Start the fabric network:

     vagrant@vagrant: ./startFabric.sh

After network started, run the two javascript to enroll admin and register user:

     vagrant@vagrant: node enrollAdmin.js
     vagrant@vagrant: node registerUser.js

Run the application with node:

    vagrant@vagrant: node server.js

    - Go to => http://localhost:8080



