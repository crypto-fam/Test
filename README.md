## Installation script :

This is a complete guide to setup a Masternode for Veco Coin.  The method used here is to use a "cold" Windows wallet with a "hot" Ubuntu 16.04 Linux VPS.  The reason for this is so your coins will be safe in your Windows wallet offline and the VPS will host the Masternode, but will not hold any coins.

## Requirements

1. Download the latest Veco Windows wallet here [ADD LINK]
2. Exactly 1000 VECO coins sent to a new recieving address
3. Download and install Putty (PUTTY LINK) 


## Setting up the Masternode

- Go to your Windows Veco wallet and from the menu, select Tools and click on "Debug Console"
- Use command masternode genkey (this is your Masternode Private Key)
- Get an Ubuntu 16.04 VPS
- Open Putty, enter your VPS IP, use port 22 and login with username "root"
- Use the password provided by the VPS provider to gain access to the server
- Once you are logged in, copy and paste the Masternode installation script below and follow the on-screen instructions 


```bash
wget https://raw.githubusercontent.com/monacocoin-net/masternode-script-monoeci/master/install.sh && chmod +x install.sh && ./install.sh
```

---


## Error troubleshooting : 
If for some reason you dont have Git installed, you can install git with the following command:

```bash
sudo apt-get install git -y
```

If script doesn't start : 
- Check that you have write permission in the current folder
- Check that you can change permission on a file

If you are still facing issues, please get in contact with the Veco Developers on Discord (https://discord.gg/Z7j9mz6)
