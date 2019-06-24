# cryptoOS
Linux Ubuntu 18.04.02 Live boot version backup - with data persistence

Description - A Live, with data persistance, boot Ubunut 18.04 LTS distribution. This is a backup that you can easily restore with mkusb. You will install mkusb on a running Ubunut machine and restore this backup to your USB drive of 8GB or larger. 

Details - With a Ubunut Live OS you can run the machine completely off a USB drive. You turn whatever computer you wish to use, Linux, macOS, or Windows, on with the created USB drive installed. You select the boot order by pressing F9/Delete/F12/ during bios boot for Linux and Windows. On a Mac you hold down the option key, next to the Apple Command key, just as the computer dings. This happens when you reboot or power on your Mac. After a few minutes you will have full access to the computer hardware you are using with the full Ubunut OS from your USB. What makes this version so special is that it allows you to write data to the USB and retrieve it even after a reboot. This is the data persistance. NOTE: If you restart the computer, the drive is returned to the last saved data state. Data is saved when you shut down the machine, NOT when you reboot. If you make changes and reboot the computer you will be promted to eject the drive and then restart the machine. This is the shutdown screen you want to see, so you will know that data was written. 

Software & Wallets - Installed software included
- Electrum: You can run a lite version secured with a hardware device. This would represent a very secure part of your drive, being your interface with your Bitcoin wallet using Electrum's light client. You don't download the blockchain with this wallet and your keys are stored on your hardware wallet.
- Coinomi: Multi non-custodial alt coin wallet, over 125 blockchains. All secured with cold storage, you control your keys generated from your munmomic seed using HD wallets (BIP44). Cold Staking, Native SegWit, No KYC, No IP association, No trasnactions tracking. Exchanges also built in but they all have KYC.
- 




Needed Items
- A computer running on Ubuntu 18.04.02  
- USB Drive at least 8GB
- mkusb installed per this tutorial
TUTORIAL: https://www.howtogeek.com/howto/14912/create-a-persistent-bootable-ubuntu-usb-flash-drive/
SOURCE: https://help.ubuntu.com/community/mkusb#Persistent_live_systems
- A copy of the ISO of Ubunut 18.04.02 on the desktop that will run mkusb
SOURCE: https://ubuntu.com/download/desktop

cryptoOS Beat verion 0.1.0 
- https://www.dropbox.com/s/ibayp4r8nl7q9nd/mkusb-backup-home.tar.gz?dl=0


Directions 
- Make sure your 8GB+ USB drive is ready to be formated
- Start on your running Linux machine with the USB drive installed
- You will follow the directions to install with mkusb in the link above under "mkusb tutorial"
- First you have to create a stock Ubunut Live USB drive so mkusb can format the drive correctly
- When your drive has been created, open mkusb again and select "Restore persistent live home" 





