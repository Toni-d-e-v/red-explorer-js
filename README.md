# Avrio-Blockchain-Explorer
Block explorer for Avrio CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon avriod. It should be accessible from the Internet. Run avriod with open port as follows:
```bash
./avriod --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=24524
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf
Adapted to avrio:
    @leocornelius

Donate: 
### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
