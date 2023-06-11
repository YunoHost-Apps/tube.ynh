<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Tube for YunoHost

[![Integration level](https://dash.yunohost.org/integration/tube.svg)](https://dash.yunohost.org/appci/app/tube) ![Working status](https://ci-apps.yunohost.org/ci/badges/tube.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/tube.maintain.svg)

[![Install Tube with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Tube quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Tube is a Youtube-like (without censorship and features you don't need!) Video Sharing App written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed.

### Features

- Easy to add videos (just move a file into the folder)
- Easy to upload videos (just use the builtin uploader and automatic transcoder!)
- Builtin ffmpeg-based Transcoder that automatically converts your uploaded content to MP4 H.264 / AAC
- Builtin automatic thumbnail generator
- No database (video info pulled from file metadata)
- No JavaScript (the player UI is entirely HTML, except for the uploader which degrades!)
- Easy to customize CSS and HTML template
- Automatically generates RSS feed (at /feed.xml)
- Clean, simple, familiar UI


**Shipped version:** 1.2.0~ynh3

**Demo:** https://tube.mills.io

## Screenshots

![Screenshot of Tube](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://tube.mills.io>
* Upstream app code repository: <https://git.mills.io/prologic/tube>
* YunoHost documentation for this app: <https://yunohost.org/app_tube>
* Report a bug: <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/tube_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
or
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
