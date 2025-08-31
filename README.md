# Irys-CLI
Details guide

Today i waii be guaid a CLI guide for Irys: 

1st part: 
-Install All Require Dependecies: 

```sudo apt-get update && sudo apt-get upgrade -y```

```sudo apt install curl iptables build-essential git wget lz4 jq make protobuf-compiler cmake gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev screen ufw -y```


Install nodejs & npm: 

```curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt install -y nodejs```


-Check Version: 

```node -v```
```npm -v```


-CLI Installation:

```sudo npm i -g @irys/cli```
