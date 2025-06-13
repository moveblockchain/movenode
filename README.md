<h1 align="center"> MOVE Blockchain Node</h1>

<p align="center">


MOVE node is a host connected to the blockchain network with the following functions:


- [REST API](https://api.moveblockhain.org)


Learn more about Nodes in the [documentation](https://moveblockchain.org).

## 🚀️ Getting started

A quick introduction of the minimal setup you need to get a running node. 

*Prerequisites:*
- configuration file `move*.conf` for a needed network from [here](releases](https://github.com/moveblockchain/movenode/releases)
- `move-all*.jar` file from [releases](https://github.com/moveblockchain/movenode/releases) 

Linux systems:
```bash
sudo apt-get update
sudo apt-get install openjdk-8-jre
java -jar node/target/move-all*.jar path/to/config/move.conf
```

Mac systems (assuming already installed homebrew):
```bash
brew cask install adoptopenjdk/openjdk/adoptopenjdk8
java -jar node/target/move-all*.jar path/to/config/move.conf
```

Windows systems (assuming already installed OpenJDK 8):
```bash
java -jar node/target/move-all*.jar path/to/config/move.conf
```
