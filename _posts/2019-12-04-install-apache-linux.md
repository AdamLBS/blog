---
title: "Install Apache/MariaDB/PHP on Debian/Ubuntu in 2 minutes "
date: 2019-12-05T19:34:30-04:00
categories:
  - blog
  - Tutorial
tags:
  - Apache
  - script
  - bash
  - PHP
  - Bungeecord
---

Install Apache, MariaDB & PHP 7 with extensions at the same time can be tought and take some time. That's why in this tutorial I will explain how to install all the basic prerequisites for a basic and complete web server.

The script that we will be using can install Apache, MariaDB, PHP 7 and its extensions but also PhpMyAdmin. You can choose to only install Apache or MariaDB...




* [Requirements](#system-requirements)
* [Features](#features)
* [Supported versions](#supported-versions)
* [Installing](#installing)
* [Launch](#launch)
* [Updating](#updating)
* [Bugs](#bugs)

# Requirements

* Unix-like OS

* curl


# Features 

* Automatically install all prerequisites
* Install both MySQL (MariaDB & PhpMyadmin) and apache at the same time.
* Using the latest stable versions of Apache, MariaDB, PHP and PHPMyAdmin.


# Supported versions
* PHP 7
* Apache 2
* Latest version of MariaDB

# Installing

* **curl** is required to download the script.

* If you are logged in as root :

```bash
curl https://uploads.admlbs.fr/download.php?file=apache --output /usr/bin/apache && chmod 0777 /usr/bin/apache
```

* If it's not the case : 

```bash
sudo curl https://uploads.admlbs.fr/download.php?file=apache --output /usr/bin/apache && chmod 0777 /usr/bin/apache
```

# Launch

* To launch the script and install a server you must use sudo or being root

```bash
apache install
```

* To see all commands please type 

```bash
apache help
```
# Updating

* To update the script you must use sudo or being root

```bash
apache update
```
# Bugs


* This script is suggested to be updated. Please report all bugs to adam@admlbs.fr
