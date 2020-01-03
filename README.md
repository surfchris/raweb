*Modification*: Rewrote the original .asp (Classic ASP, vbscript) to .aspx (ASP.NET using C#). I rewrote it because Classic ASP is incompatible with mono-project for running on Linux/FreeBSD. Everything should work the same way, just new Default.aspx, webfeed.aspx, and Web.config
--*surfchris*

# RAWeb

A simple web interface for your RemoteApps hosted on Win 7, 8, 10 and Server.

To setup RemoteApps, try [RemoteApp Tool](https://github.com/kimmknight/remoteapptool).

## Features

* A web interface for your RemoteApps (and full-desktop RDP sessions)
* Webfeed to put RemoteApps in client start menu
* Optional authentication to provide different apps to different users
* File type associations on webfeed clients

## Download

[Latest](https://github.com/kimmknight/raweb/archive/master.zip)

## Installation

1. Install IIS and ASP features
2. Copy the contents of the "wwwroot" folder to your inetpub\wwwroot folder.

## Guides

* [Setup RAWeb Web Interface](https://github.com/kimmknight/raweb/wiki/Setup-RAWeb-Web-Interface)
* [Setup RAWeb Webfeed with a Self Signed Certificate](https://github.com/kimmknight/raweb/wiki/Setup-RAWeb-Webfeed-with-a-Self-Signed-Certificate)
* [File type associations for RAWeb webfeed clients](https://github.com/kimmknight/raweb/wiki/File-type-associations-for-RAWeb-webfeed-clients)
* [Configuring RAWeb for a multi user environment](https://github.com/kimmknight/raweb/wiki/Configuring-RAWeb-for-a-multi-user-environment)

## Screenshots

![](https://github.com/kimmknight/raweb/wiki/images/screenshots/raweb0020.png)

A web interface for your RemoteApps

![](https://github.com/kimmknight/raweb/wiki/images/screenshots/rawebfeed.png)

Webfeed puts RemoteApps in client Start Menu

![](https://github.com/kimmknight/raweb/wiki/images/screenshots/win8webfeedcrop.jpg)
