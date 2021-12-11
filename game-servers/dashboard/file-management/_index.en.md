+++
title = "File Manager/FTP"
date =  2021-03-24T22:10:47-04:00
weight = 101
+++

## File Management with Pterodactyl
There are two ways to manage your server files; FTP and the built-in file manager.

### Using FTP
By far the most recommended way to manage your server files is to use FTP, otherwise known as File Transfer Protocol. FileZilla and WinSCP are the two most common FTP programs, both boasting their own benefits and drawbacks, but it comes down to personal preference. This page will go over both and how to use them with your ArkTech game server.

#### Connecting Using WinSCP
1. Navigate to the Settings tab of your game panel.
![Screenshot](/game-servers/images/settings.png)
2. Your FTP information will be listed under "SFTP Details".
3. Install and launch WinSCP. Upon startup, you will be prompted for FTP information. Input your details into the respective boxes. Please be sure to mark the protocol as SFTP.
![Screenshot](/game-servers/images/settings2.png)
4. Hit login you will be presented with your server files. You are all set!

#### Connecting Using FileZilla
1. Navigate to the Settings tab of your game panel.
![Screenshot](/game-servers/images/settings.png)
2. Your FTP information will be listed under "SFTP Details".
3. Install and launch FileZilla. In order to connect, navigate to File > Site Manager to open the site manager.
4. Click new site. Input your FTP details into the respective boxes. Please be sure to mark the protocol as SFTP.
![Screenshot](/game-servers/images/settings3.png)
5. Hit connect and you will be presented with your server files. You are all set!

### Using the File Manager
An alternative to FTP is using Pterodactyl's built-in file manager. While less convenient, it is an option that some may prefer. All of the useful files pertaining to your server will be located in `home/container/garrysmod`.

#### File Manager Actions
1. Create Directory
    - Creates a new folder.
1. Upload
    - Allows you to upload files from your own computer.
1. New File
    - Creates a new text file, with options to change the file extension.

---
#
This page written by [wizerd](/contributors/wizerd/).
![Banner](/images/fishy.gif)