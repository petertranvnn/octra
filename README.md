


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
### install Octra client
1.
```
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
```
2.
```
python3 -m venv venv
```
3.
```
source venv/bin/activate
```
4.
```
pip install -r requirements.txt
```
5.
```
cp wallet.json.example wallet.json
```
6.
```
nano wallet.json
```
7.
```
./run.sh
```
