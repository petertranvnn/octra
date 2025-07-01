


### Tạo ví

```
curl -fsSL https://octra.org/wallet-generator.sh | bash
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
