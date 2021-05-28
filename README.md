# keys

```
curl https://raw.githubusercontent.com/whalewave-net/keys/main/authorized_keys > ~/.ssh/authorized_keys
```

```
curl https://raw.githubusercontent.com/whalewave-net/keys/main/known_hosts > ~/.ssh/known_hosts
```

```
curl https://raw.githubusercontent.com/whalewave-net/keys/main/x509.whalewave.net.pem > whalewave-net.crt
sudo cp whalewave-net.crt /usr/local/share/ca-certificates/whalewave-net.crt
sudo update-ca-certificates
```
