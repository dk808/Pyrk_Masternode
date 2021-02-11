# Pyrk Masternode
Script needs to be ran under a sudo user and not under root. It will install latest binaries, configure basic firewall settings(optional), install sentinel(optional), and create a daemon service for you. It also has a bootstrap option for quick syncing.

> ℹ Note: This has only been tested on Ubuntu 18. USE AT OWN RISK.

## Installation
Create a sudo user and run this under that sudo user. Script will exit if ran under root.  
Script will ask for BLS Secret Key(operatorSecret) that you get from the bls generate command. So have it ready.
```bash
bash <(curl -s https://raw.githubusercontent.com/dk808/Pyrk_Masternode/main/install.sh)
```
> ℹ Info: This will also create a script to update binaries.  

If you need any support please join their [Discord](https://discord.gg/4FrYVZJpkD).
