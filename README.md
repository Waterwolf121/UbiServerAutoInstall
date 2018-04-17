# UbiServerAutoInstall

Átírni: -vmname
        -ostype (Ubuntu_64/Windows7)
        -isofile (telepítő isofájl helyének megadása)
        -hddfile (/home/felhasználónév/${vmname}/${vmname}.vdi)
        -vboxmanage modifyvm $vmname --nic1 bridged --bridgeadapter1 enp2s0 --cableconnected1 on (eth0/enp2s0)
      
GLHF
