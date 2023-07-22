***********************************

linux

for i in {1..30}; do bitcoin-cli -rpcwallet="/root/.bitcoin/walletname/" getnewaddress " " "bech32"; done


Win 

1.copy  .conf to roaming , localization blocks in .conf datadir= + wallet=

2.run coin daemon.exe 

3.run powershell cd F:\folder\coinfolder

4.for ($i=1; $i -le 100; $i++) {.\bitcoin-cli -rpcwallet="F:\folder\coinfolder\walletfolder" getnewaddress " " "bech32"}



