---
title: "Install a Minecraft Spigot and Bungeecord Server Easily"
date: 2019-12-05T15:34:30-04:00
categories:
  - blog
  - Tutorial
tags:
  - Minecraft
  - script
  - bash
  - Spigot
  - Bungeecord
---
* [Introduction](#intro)
* [Requirements](#system-requirements)
* [Features](#features)
* [Supported versions](#supported-versions)
* [Installing](#installing)
* [Launch](#launch)
* [Updating](#updating)
* [Bugs](#bugs)
* [License](#license)

# Intro

Sometimes installing a minecraft server can be laborious, install java 8 and its dependencies too, that's why in this tutorial I will explain you how to install a Minecraft Spigot and Bungeecord Server Easily without any knowledge. To do this we will use a bash script which is available in my own Github Page.

# Requirements

* Unix-like OS

* curl




# Features 

* Auto-Updater
* Automatically install all prerequisites
* Install both BungeeCord and Spigot at the same time.
* Using the latest stable versions of Spigot.


# Supported versions
* 1.8
* 1.9.x
* 1.10.x
* 1.11.x
* 1.12.x
* 1.13.x
* Latest version of Spigot.
* Latest version of Bungeecord

# Installing

* **curl** is required to download the script.

* If you are logged in as root 
```bash
curl https://uploads.admlbs.fr/download.php?file=mcinstall --output /usr/bin/mcinstall && chmod 0777 /usr/bin/mcinstall
```

* If it's not the case : 

```bash
sudo curl https://uploads.admlbs.fr/download.php?file=mcinstall --output /usr/bin/mcinstall && chmod 0777 /usr/bin/mcinstall
```

# Launch

* To launch the script and install a server you must use sudo or being root

```bash
mcinstall install
```

* To see all commands please type 

```bash
mcinstall help
```
# Updating

* To update the script you must use sudo or being root

```bash
mcinstall update
```


