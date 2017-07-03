# Simple NFS GUI for Linux

![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/27803265-f3ab49dc-6028-11e7-8e10-857f86ac5a85.png)
![screenshot2 Linux](https://user-images.githubusercontent.com/24923693/27803341-3c222398-6029-11e7-909e-47fd10f8da30.png)
![screenshot3 Linux](https://user-images.githubusercontent.com/24923693/27803354-473c5898-6029-11e7-9e24-9f6bd7ee686a.png)



## Install

Application written in Visual Basic Gambas. 

1. Open terminal and add the PPA for the language Gambas
  ```
  $ sudo add-apt-repository ppa:gambas-team/gambas3
  $ sudo apt-get update 
  ```
2. Download the package .deb and install it.
3. The dependancy for the Gambas language will be automatically installed.


## Settings

This app allow you to set a machine as a Client or/and as Server in a local network, using the NFS protocol for Linux. This is a front-end for NFS, a GUI tool for NFS. In order to set a machine as Client/Server, you need to run this app as root, with sudo or gksudo for exemple.

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


[![download][2]][1]

  [1]: https://github.com/Philippe734/Simple.NFS.GUI/raw/master/Linux/1.0.9/Setup_Simple_NFS_GUI_1.0.9_all.deb
  [2]: https://cloud.githubusercontent.com/assets/24923693/21723900/7fdda69e-d432-11e6-8ab1-87dd79f36fe5.gif
