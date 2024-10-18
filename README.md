# TESTNET NUBIT

#UPDATE & UPGRADE
```
sudo apt update && sudo apt upgrade -y
```

# SCREEN NEW
```
screen -S nubit
```

#INSTALL NUBIT
```
curl -sL1 https://nubit.sh | bash
```

CLOSE SCREEN
* CTRL  + A + D
  #VIEW MNEMONIC
```
cd nubit-node && sudo cat mnemonic.txt
```

#BACK TO SCREEN
```
screen -r nubit
```

#REMOVE NDOE
```
pkill -f nubit

rm -rf nubit-node

rm -rf $HOME/.nubit-light-nubit-alphatestnet-1
```
