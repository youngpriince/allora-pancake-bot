# allora-pancake-bot
![Screenshot (103)](https://github.com/user-attachments/assets/5b538a66-2411-4c3b-bef3-9eb07c2dca0a)



* Connect your EVM metamask wallet [here](https://app.allora.network?ref=eyJyZWZlcnJlcl9pZCI6IjVmNmUwNmMwLTU5YzQtNDM1NC05MmIxLWFmMzcyYjA1ZTgyMSJ9)
* The more we bet on [pancake](https://pancakeswap.finance/prediction?token=ETH&chain=arb) the more we get Allora points

## Install Dependecies
```console
sudo apt-get update
sudo apt install git screen python3 python3-pip

pip3 install web3
#OR
pip install web3
```
```console
git clone https://github.com/youngpriince/allora-pancake-bot
cd allora-pancake-bot
```

## Run Bot
* We can run 1 or 2 wallets with betting x amount of ETH per epoch
* 2 Wallets with opposite bets decrease the risk
### Wallet 1
```console
screen -S bull

python3 bet-bull.py
```
Ctrl+A+D


### Wallet 2
```console
screen -S bear

python3 bet-bear.py
```
Ctrl+A+D

