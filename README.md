# OpenVPN-Ubuntu-18.04-Offline
##Installs and configure OpenVPN in an isolated network for special use-cases.

*SFTP into the target Ubuntu 18.04 server

```sftp example_user@target_server_ip```

*Upload the contents of this repository to the server

```put ./* .```

*Exit the SFTP server*

```exit```

*SSH into the target server

```ssh example_user@target_server_ip```

*Make the openvpn-install script executable

```chmod +x openvpn-install.sh```

*Execute the script with sudo priviledges

```sudo ./openvpn-install.sh```

*SFTP back into the target server

```sftp example_user@target_server_ip```

*Download the client.ovpn file

```get client.ovpn .```

*Exit the SFTP server*  

```exit```

*Double click the client.ovpn file in Finder to install the VPN configuration to Tunnelblick
