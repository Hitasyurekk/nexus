# nexus

```

screen -S nexus


sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh
. "$HOME/.cargo/env"

reboot

sudo apt install -y protobuf-compiler

echo "PROVER_ID" > ~/.nexus/prover-id
curl https://cli.nexus.xyz/ | sh

```
