#  ownCloud Quick Start

ownCloud is an open-source application for secure file sync, sharing, and collaboration via a single point of access. Teams can work on their data from any location and with any device.

This quick start is relevant for ownCloud Server v10.8 and is intended for:
- Administrators who want to install and configure an ownCloud server, and enable server access for users. 
- Users who want to connect to an ownCloud server via a desktop or mobile client.


1. Admins: Before you install
1. Admins: Download the relevant ownCloud package for your environment
1. Admins: Install the ownCloud package on your server
1. Admins: Configure the ownCloud server
1. Admins: Add users and enable access
1. Users: Connect to an ownCloud server


##  What do I need to do before I install the ownCloud server? 

This section points you to the requirements, prerequisites, and preparations you need to make for your environment  

* Verify that your system meets the [system requirements](https://doc.owncloud.com/server/10.8/admin_manual/installation/system_requirements.html) for the ownCloud server installation. 

### Prepare your server 

- [Ubuntu 20.04 preparation guide for PHP 7.4](https://doc.owncloud.com/server/10.8/admin_manual/installation/manual_installation/server_prep_ubuntu_20.04.html)
- [Ubuntu 18.04 preparation guide for PHP versions up to 7.3](https://doc.owncloud.com/server/10.8/admin_manual/installation/manual_installation/server_prep_ubuntu_18.04.html)
### Install a database

### Configure the Apache web server

### Install ownCloud binaries for your package

### Download ownCloud 
The most common installation options are Choose the installation option that's right for your environment:
    - Customizable installation, recommended for production environments with the ownCloud .zip archive or .tar file
    - Manual installation on Linux: ownCloud .tar file : 
       -Prerequisites:
       [Required](https://doc.owncloud.com/server/10.8/admin_manual/installation/manual_installation/manual_installation_prerequisites.html#required-prerequisites)
       [Recommended](https://doc.owncloud.com/server/10.8/admin_manual/installation/manual_installation/manual_installation_prerequisites.html#recommended-prerequisites) 
       [Optional](https://doc.owncloud.com/server/10.8/admin_manual/installation/manual_installation/manual_installation_prerequisites.html#optional)
      
    - Linux distribution bundle: hosted on openSUSE 
    - Docker environment: Uses Docker Compose with the ownCloud YAML file
    - Script-guided installation


|Environment|
|---|
|Production environments: Download the [.zip or .tar source package](https://owncloud.com/download-server/#source-packages) and install.<br>Minimal installations for [Ubuntu 18.4](https://doc.owncloud.com/server/10.8/admin_manual/installation/quick_guides/ubuntu_18_04.html) or [Ubuntu 20.4](https://doc.owncloud.com/server/10.8/admin_manual/installation/quick_guides/ubuntu_20_04.html) |
|Linux distributions: Select the Linux distribution package for your OS vendor, then [Add the repository and install manually](https://doc.owncloud.com/server/10.8/admin_manual/installation/manual_installation/) **~ or~** [grab the binary packages for a single-server setup](https://software.opensuse.org/download/package?package=owncloud-complete-files&project=isv%3AownCloud%3Aserver%3A10).|
|Docker container: Download the [ownCloud Server Docker image](https://doc.owncloud.com/server/10.8/) and use the [ownCloud YAML with Docker Compose](https://doc.owncloud.com/server/10.8/admin_manual/installation/docker/).

<!-- what are the installation procedures?  There are so many options, I can't map them to the different downloads-->


## What are my installation options and where can I download the installation files from? 


## Installing ownCloud Server v10.8 

[Linux package manager installation](https://doc.owncloud.com/server/10.8/admin_manual/installation/linux_packetmanager_install.html#add-the-owncloud-repository) 

### How do I install ownCloud Server? 



1. Download the installation package




cvv


## Configuring the ownCloud server

Configure the server IP address and port

The configuration file location

Customize the proxy parameters
| Variable |Default| Description|
|---|---|---|
|host|127.0.0.1|Proxy server address|
|port|8080| Listener port for the proxy|
|type | 2| Proxy types: <br> * **0** for System <br> * **1** for SOCKS5<br> * **2** for No proxy<br>* **3** for HTTP(S) |




## Adding a user acount to connect to the ownCloud Server

 Add a user account



## How do I download, install, and configure my ownCloud client?

Use the newest ownCloud desktop synchronization client for your ownCloud server. 
Download the client [here]( <!-- placeholder -->).
The detailed desktop client requirements are [here.](https://doc.owncloud.com/desktop/2.9/installing.html#system-requirements|


## How do I connect to the ownCloud server?

You can use the following web servers: 

- Connect to your ownCloud server via a desktop or mobile client




