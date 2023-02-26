# Simple NFS GUI for Linux

[![Download][2]][1]

  [1]: https://github.com/Philippe734/Simple.NFS.GUI/releases
  [2]: https://docs.appimage.org/_images/download-appimage-banner.svg

![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/27803265-f3ab49dc-6028-11e7-8e10-857f86ac5a85.png)
![screenshot2 Linux](https://user-images.githubusercontent.com/24923693/27803341-3c222398-6029-11e7-909e-47fd10f8da30.png)
![screenshot3 Linux](https://user-images.githubusercontent.com/24923693/27803354-473c5898-6029-11e7-9e24-9f6bd7ee686a.png)

## Install

Release available in AppImage, indeed after some years!

### French video tuto release 1.0.40

[![Watch the video]](https://user-images.githubusercontent.com/24923693/221423865-c44d7236-fd57-49f8-a19b-3f8c16195ff7.mp4)

## Settings

This app allow you to set a machine as a Client or/and as Server in a local network, using the NFS protocol for Linux. This is a front-end for NFS, a GUI tool for NFS. Reboot the machine(s) after settings.

/!\ Clients and servers must have static IP addresses
### Set a machine as a Client

1. Select the option Client or Client+Server
2. Click on ... to find the Server
3. Select the IP of the Server
4. Type the full path of the data shared by the Server
5. Type a name for the mount point on the Client
6. Click to set the machine as a Client


### Set a machine as Server

1. Select the option Server or Client+Server
2. Click on ... to find a Client
3. Select the IP of the Client
4. Type the full path of the data shared by the Server
5. Click to set the machine as Server
6. Rerun this procedure for each Client

### What does this app do ?

* Install packages relevant to NFS, including `fping`, `nfs-common` and `nfs-kernel-server`
* Edit the following files for a Server : /etc/exports ; /etc/hosts.deny ; /etc/hosts.allow
* Edit /etc/fstab for a Client
* Make a dir for the client's mount point

### Delete NFS settings

* You have to edit `/etc/fstab` and `/etc/exports` to remove entries about NFS
* In future, maybe I will add option to remove it by my app

[![Download][2]][1]
