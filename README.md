Technical specifications:
---------------------
Algorithm: X11,
Maximum coins: 10.000.000,
Time between blocks: 3 minutes,
Block reward: 10 DXBC,
Port RPC: 3548,
Port P2P: 3848.

Compile GUI Wallet (Test on Ubuntu 16.04 and 17.10):
---------------------

```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git
git clone https://github.com/Dubaicash/Dubaicash
cd Dubaicash
chmod +x compile.sh
./compile.sh
./Dubaicash-qt
```
