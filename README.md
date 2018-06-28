# Example app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/REPLACEBYYOURAPP.svg)](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20%28Community%29/lastBuild/consoleFull)  
[![Install REPLACEBYYOURAPP with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=REPLACEBYYOURAPP)

> *This package allow you to install REPLACEBYYOURAPP quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Quick description of this app.

**Shipped version:** 1.0

## Screenshots

![](Link to an screenshot for this app)

## Demo

* [Official demo](Link to a demo site for this app)

## Configuration

How to configure this app ? By an admin panel, an plain file with ssh, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: There no other documentations, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Is LDAP and HTTP auth supported ?
Can the app be used by multiple users ?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)%20(%7EARM%7E)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/REPLACEBYYOURAPP%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/REPLACEBYYOURAPP%20(Community)/)

## Limitations

* Any known limitations.

## Additionnal informations

* Other informations you would add about this application

### Usage of this package
- Copy this app before working on it.
- Edit `conf/nginx.conf` file to match application prerequisites.
- Edit `manifest.json` with application specific information.
- Edit the `install`, `upgrade`, `remove`, `backup`, and `restore` scripts.
- Add a `LICENSE` file for the package.
- Edit `README.md`.

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/issues
 * APP website: Link to the official website of this app
 * YunoHost website: https://yunohost.org/

---

Developers infos
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --verbose
or
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --verbose
```
