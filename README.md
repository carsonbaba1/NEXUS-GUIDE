# **NEXUS-GUIDE - CLI**

 # 1.  INSTALL ALL REQUIREMENTS.

```bash
  sudo apt update
```

```bash
sudo apt upgrade
```

```bash
 sudo apt install build-essential pkg-config libssl-dev git-all
 ```

```bash
  sudo apt install protobuf-compiler
```


# 2. INSTALL RUST

```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```


```bash
  git clone git@github.com:nexus-xyz/nexus-cli.git
```

```bash
  cd clients/cli
```


```bash
  cargo build --release
```

# QUICK INSTALLATION 

```
curl https://cli.nexus.xyz/ | sh
```

# START COMMAND 

```
nexus-network start --node-id <your-node-id>
```

EDIT <your-node-id> WITH YOUR CLI/NODE ID 



  git clone git@github.com:nexus-xyz/nexus-cli.git
