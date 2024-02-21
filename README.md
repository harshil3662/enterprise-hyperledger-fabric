Hyperledger Fabric Fishing Sample App

Prerequisite:

- Set up Ubuntu on VirtualBox with Vagrant (recommended Ubuntu v16.04 LTS)
- Set up Docker, Docker-Compose
- Install Golang
- Install Node, npm

Blockchain Network:

- Go to network folder and run script for network configuration:

     harshil@harshil: ./generate.sh

Start the fabric network:

     harshil@harshil: ./startFabric.sh

After network started, run the two javascript to enroll admin and register user:

     harshil@harshil: node enrollAdmin.js
     harshil@harshil: node registerUser.js

Run the application with node:

    harshil@harshil: node server.js

    - Go to => http://localhost:8080



