# Simple NFS GUI for Linux

![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/27803265-f3ab49dc-6028-11e7-8e10-857f86ac5a85.png)
![screenshot2 Linux](https://user-images.githubusercontent.com/24923693/27803341-3c222398-6029-11e7-909e-47fd10f8da30.png)
![screenshot3 Linux](https://user-images.githubusercontent.com/24923693/27803354-473c5898-6029-11e7-9e24-9f6bd7ee686a.png)



## Install

Download the package, install it and get the dependencies with this one line commands:
  ```
  sudo add-apt-repository ppa:gambas-team/gambas3 -y ; sudo apt-get update ; wget https://github.com/Philippe734/Simple.NFS.GUI/raw/master/Linux/1.0.15/simple-nfs-gui_1.0.15-0ubuntu1_all.deb -P ~ ; sudo dpkg -i ~/simple-nfs-gui_1.0.15-0ubuntu1_all.deb ; sudo apt-get install -fy ; rm ~/simple-nfs-gui_1.0.15-0ubuntu1_all.deb
  ```


## Settings

This app allow you to set a machine as a Client or/and as Server in a local network, using the NFS protocol for Linux. This is a front-end for NFS, a GUI tool for NFS. In order to set a machine as Client/Server, you need to run this app as root, with sudo -H or gksu. Reboot the machine after settings.

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

* Install the minimal package relevant to NFS.
* Edit the following files for a Server : /etc/exports ; /etc/hosts.deny ; /etc/hosts.allow
* Edit /etc/fstab for a Client
* Make a dir for the mount point for a Client

## Profile

![youhou](https://cloud.githubusercontent.com/assets/24923693/21691776/43084e80-d37a-11e6-9571-5c6c60c19964.gif)

I'm the author of the famous VPN Lifeguard. If you want to reward my work, or thank me, then you can [donate](http://vpnlifeguard.blogspot.fr/p/faire-un-don.html) a few dollars [HERE](http://vpnlifeguard.blogspot.fr/p/faire-un-don.html) and I'll be very happy!

[![download][2]][1]

  [1]: https://github.com/Philippe734/Simple.NFS.GUI/raw/master/Linux/1.0.15/simple-nfs-gui_1.0.15-0ubuntu1_all.deb
  [2]: https://cloud.githubusercontent.com/assets/24923693/21723900/7fdda69e-d432-11e6-8ab1-87dd79f36fe5.gif
