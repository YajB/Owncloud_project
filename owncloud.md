#  ownCloud Quick Start

ownCloud is an open-source application for file sync, share, and content collaboration that lets teams work on their data from anywhere and on any device.

This quick start provides instructions to install ownCloud server and connect to it via a desktop or mobile client 

## Installing and configuring ownCloud Server v10.8 

### Prerequisites


- Configure the server IP address and port
- Enable a user to connect to the ownCloud Server
- Add a user account

### Server package options
+ [Source Packages for production environments](https://owncloud.com/download-server/#source-packages)
Download the .zip or .tar package
The .zip file includes the following 




+ [Linux distribution packages for RedHat Enterprise Linux (RHEL) and other Linux OS options](https://software.opensuse.org/download/package?package=owncloud-complete-files&project=isv%3AownCloud%3Aserver%3A10)
+ [Docker image](https://doc.owncloud.com/server/10.8/)
## Configuring the ownCloud client

The configuration file location

Customize the proxy parameters
| Variable |Default| Description|
|---|---|---|
|host|127.0.0.1|Proxy server address|
|port|8080| Listener port for the proxy|
|type | 2| Proxy types<br> 0 for System <br> **1** for SOCKS5<br> **2** for No proxy<br>**3** for HTTP(S) |



## Connecting to ownCloud server
- Connect to your ownCloud server via a desktop or mobile client




