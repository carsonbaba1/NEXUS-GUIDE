# **NEXUS-GUIDE - CLI**

# 1. MAKE A SCREEN 

```bash
screen -S NEXUS
```

 # 2.  INSTALL ALL REQUIREMENTS.

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


# 3. INSTALL RUST

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

# 4. QUICK INSTALLATION 

```
curl https://cli.nexus.xyz/ | sh
```

# 5. START COMMAND 

```
nexus-network start --node-id <your-node-id>
```

EDIT <your-node-id> WITH YOUR CLI/NODE ID 

❓ # HOW TO GET NODE ID ?

# 1. VISIT THE WEBSITE https://app.nexus.xyz/nodes

![image](https://github.com/user-attachments/assets/8ad3e641-d760-42c0-83fd-0a0ab3d2868b)

# 2. NOW CLICK ON ADD CLI - U WILL GET THE NODE ID 
![image](https://github.com/user-attachments/assets/0307d668-4c4a-4cd9-ab3d-ca6cd0f777a5)





# IF U HAVE ANY PROBLEM DM ME IN TG - @Babacarson
# ALSO JOIN MY TELEGRAM CHANNEL - http://t.me/weekshit_show
