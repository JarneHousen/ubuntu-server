# Installation

## steamCMD

https://www.imaginelinux.com/install-steamcmd-on-ubuntu/
https://developer.valvesoftware.com/wiki/SteamCMD

Creating user
```
jarne@ubuntu-server:~$ sudo sudo useradd -m steam
jarne@ubuntu-server:~$ sudo passwd steam
New password: 
Retype new password: 
passwd: password updated successfully
jarne@ubuntu-server:~$ sudo -u steam -s
steam@ubuntu-server:/home/jarne$ cd /home/steam
```

Installing steamCMD
```
sudo add-apt-repository multiverse; sudo dpkg --add-architecture i386; sudo apt update
sudo apt install steamcmd

```
## Podman
https://podman.io/docs/installation#linux-distributions

Installing podman
```
sudo apt-get update
sudo apt-get -y install podman
```

## Starting Valheim container

https://github.com/mbround18/valheim-docker

