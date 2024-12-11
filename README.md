# nexus

```

screen -S nexus


sudo apt update && sudo apt upgrade -y
sudo apt install -y protobuf-compiler
sudo apt install -y pkg-config
sudo apt install libssl-dev
mkdir -p ~/.nexus


echo "PROVER_ID" > ~/.nexus/prover-id


curl https://cli.nexus.xyz/ | sh

```

Hata alırsanız
```
curl https://cli.nexus.xyz/ | sh

apt-get install -y build-essential

apt-get update
apt-get install -y protobuf-compiler


```
```
Flag hatası alanlar için 

cd /root/.nexus/network-api/clients/cli

nano build.rs

Eğer build.rs içinde protoc komutu veya prost_build / tonic_build fonksiyonları çağırılırken --experimental_allow_proto3_optional bayrağı eklenmişse, o satırı bulun ve ilgili bayrağı silin.

cargo clean
cargo build --release
```
