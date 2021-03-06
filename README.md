Utum crypto

# UTUM setup files (updated by UTUM Community) 

## Key links
- Setup instructions: https://github.com/robcrypto2/Utum/raw/master/wallets/utum_linux_mn_setup_guide_v2.pdf
- Wallets: https://github.com/robcrypto2/Utum/tree/master/wallets
- Announcement: https://bitcointalk.org/index.php?topic=3471007.0
- Github: https://github.com/robcrypto2/Utum/
- Discord: https://discord.gg/VArqJWg
- Buy UTUM at Graviex: https://graviex.net/markets/utumbtc

## Linux VPS masternode setup script 
```
wget https://raw.githubusercontent.com/robcrypto2/Utum/master/masternode.sh 
chmod 755 masternode.sh 
./masternode.sh
```

## Linux VPS masternode setup script #2 (using binaries - faster install)
```
wget https://raw.githubusercontent.com/robcrypto2/utum1b/master/install_utum.sh
chmod 755 install_utum.sh 
su
bash install_utum.sh
```

## Other useful commands
```
#start masternode from Windows console where "utum_mn01" is your masternode alias
masternode start-alias utum_mn01

#masternode status
utum-cli masternode status

#restart UTUM service
systemctl restart Utum.service

#get info
utum-cli getinfo

#get blockcount
utum-cli getinfo
```

## Nodes to add to wallet.conf file
From https://utum.ccore.online/connections
```
addnode=199.247.30.12:17121
addnode=185.212.225.172:17121
addnode=167.99.157.162:17121
addnode=138.68.191.76:17121
addnode=46.166.139.73:17121
addnode=63.209.32.106:17121
addnode=158.69.209.151:17121
addnode=5.45.66.236:17121
addnode=109.235.66.7:17121
addnode=108.61.200.47:17121
addnode=46.17.41.147:17121
addnode=144.202.33.250:17121
addnode=213.136.77.231:17121
addnode=149.28.201.91:17121
addnode=45.76.250.205:17121
addnode=45.77.150.7:17121
```

## Coin Info
```
Coin name: UTUM
Coin ticker: UTUM
Algorithm: QUARK
Type: POW / POS / MN
Block Time: 1 minute
Min. staking age: 2 hours
Rewards: MN - 60%, POS - 40%
Last POW Block: 3000
Max Coin Supply: 100 000 000 
Coins required for MN:  3000
Premine: 352 000

POW + MN
Block height	Reward
1		Premine
2 - 3000	1

POS + MN
Block height		Reward
3001 - 12000		60
12001 - 22000		100
22001 - 42000		140
42001 - 100000		100
100001 - 160000		80
>160001			60
```
