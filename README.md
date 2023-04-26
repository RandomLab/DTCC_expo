# DTCC_expo

# 1. Introduction

List of computers used in exhibition :

![map of computers](./map/map.png)


# 2. Easy installation with linux iso images : 
## Router configuration [!] :

1. Settings the router in router mode
2. Settings ssid and password of the wifi network
```
ssid = ddtc
password = random2568
```

---

## For each player :
You can download the iso image on this adress : 

### Link of ENGLISH version :
[https://system.freeboxos.fr:81/share/6N-wyZYg5k9gKt06/mireos-V11_eng.iso](https://system.freeboxos.fr:81/share/6N-wyZYg5k9gKt06/mireos-V11_eng.iso)

### Link of FRENCH version :
[https://system.freeboxos.fr:81/share/yLmuux99JEPK7C92/mireos-V11_fr.iso](https://system.freeboxos.fr:81/share/yLmuux99JEPK7C92/mireos-V11_fr.iso)

How to install the iso image on a USB key :

1. Download the iso image
2. Download the software [balenaEtcher](https://www.balena.io/etcher/)
3. Open balenaEtcher and select the iso image
4. Select the USB key
5. Click on "Flash" and wait for the end of the installation
  
  
### Time to boot tiny computer on usb flash drive:  
How to boot on the USB key :

1. Plug the USB key on the computer
2. Turn on the computer
3. Press the key to enter the boot menu (F12 or del for most computers)
4. Select the USB key in the boot menu
5. Save and exit
6. At this point, the computer should boot on the USB key, it take 5 minutes to begin to view image on the screen

You also turn always power on option in the bios to avoid the computer to turn off when there is a power cut.

/!\ Repeat this operation for the 5 others players computers.

---

You can test if each computer is connected to the software Angry IP Scanner.  
you can download it on this adress : [https://angryip.org/download/](https://angryip.org/download/)
  

Exemple of the result of the scan :

![angrip scanner](./map/angryIp.png)

---

## For the game computer :

- Boot your computer with your favorite system (Windows or Linux)
- Connect the computer to the ddtc WIFI network (ssid : ddtc / pass : random2568)
- The 2 screen of the computer must be connected to the graphic card and displayed un landscape mode.
![Game Computer display](./map/display.png)
- Connect the 2 gamepads to the computer
- Connect the computer to the ddtc WIFI network

Download the game : 

Linux version :  
[https://system.freeboxos.fr:81/share/TrqkPLZGgUScgbTD/linux.zip](https://system.freeboxos.fr:81/share/TrqkPLZGgUScgbTD/linux.zip)

Windows version :  
[https://system.freeboxos.fr:81/share/RBT0y9DOTfa4e04x/windows.zip](https://system.freeboxos.fr:81/share/RBT0y9DOTfa4e04x/windows.zip)

Juste launch the game and enjoy !

![manette](./map/manette.png)

---

# Open source Random(lab)

The game and player is open source and you can find the source code on this adress :

The players :  
[https://github.com/RandomLab/DDTC_player](https://github.com/RandomLab/DDTC_player)

The Game :  
[https://github.com/RandomLab/DTCC_game](https://github.com/RandomLab/DTCC_game)