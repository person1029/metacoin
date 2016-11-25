Metacoin 1.1.0 - MET Relaunch

https://s11.postimg.org/5w2njqevj/metacoin.png

CHANGES:
The specs of the coin remain the same.
This build will start from block 0.
No coins from the previous MET will be passed over.
There will be no premine past block 1.

SYMBOL: MET

WEBSITE: tba

Source: https://github.com/person1029/metacoin/
Windows QT Download: https://github.com/person1029/metacoin/releases/

Based on quarkcoin

COIN SPECS:
- Total Coins: 140,000,000
- Block Time: 30 Seconds

ALGO:
- Quark

BLOCK REWARDS:

- 1-144,000 = 100
- 144,001-288,000 = 80
- 288,001-432,000 = 64
- 432,001-576,000 = 51
- 576,001-720,000 = 40
- 720,001-864,000 = 32
- 864,001-1,008,000 = 25
- 1,008,001+ = 20

PREMINE:
- 1 block for testing (100 MET).

CONF AND CONNECTING:
- metacoin.conf (for windows: you'll need to create this and place it in the AppData/Roaming/Metacoin directory)

addnodes:

If the wallet is not connecting at startup try
addnode=104.154.130.80
addnode=64.137.233.165
addnode=104.236.249.42

 (default ports)
rpcport=8484
port=8485
 (for solo)
server=1
rpcuser=whateverusername
rpcpassword=whateverpassword
rpcallowip=localhost

MINING:
- GPU Mining is possible.. see : https://bitcointalk.org/index.php?topic=475795 (using the quark algo)
- CPU Mining is possible.. see : https://bitcointalk.org/index.php?topic=1326803 (using the quark algo)
