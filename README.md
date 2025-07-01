


### Tạo ví
1. Clone source

```
git clone https://github.com/octra-labs/wallet-gen.git
cd wallet-gen
```

2. mở cổng
```
ufw allow 22/tcp
ufw allow 8888/tcp
ufw enable
```
3. Permision
```
chmod +x start.sh
./start.sh
```

--------------
###install Octra client

```
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
```

```
python3 -m venv venv
```

```
source venv/bin/activate
```

```
pip install -r requirements.txt
```

```
cp wallet.json.example wallet.json
```

```
nano wallet.json
```

```
./run.sh
```
