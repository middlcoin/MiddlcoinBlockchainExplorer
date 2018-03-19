# Middlcoin-Blockchain-Explorer
Block explorer for Middlcoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon middlcoind. It should be accessible from the Internet. Run middlcoind with open port as follows:
```bash
./middlcoind --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=48730
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
