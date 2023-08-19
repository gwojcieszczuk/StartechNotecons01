## Startech NOTECONS01 USB Crash Cart Adapter software, version 118.1019

![startech256.png](misc/startech256.png)
* Repackaged as AppImage (x86_64)
* [Download Link (~39MB)]()
* To be used with the following hardware:
   * [https://www.startech.com/en-us/server-management/notecons01](https://www.startech.com/en-us/server-management/notecons01)
* List of supported and tested Linux distributions


  - Debian 12 (GNOME3, KDE, XFCE)
  - Ubuntu 20.04 LTS (GNOME3, KDE, XFCE)
  - Ubuntu 22.04 LTS (GNOME3, KDE, XFCE)
  - Ubuntu 23.04 (GNOME3, KDE, XFCE)
  - Fedora 38
  - MX Linux 23
  - Manjaro (rolling)
  - openSUSE Tumbleweed (rolling)
  - openSUSE Leap 15.5
  - Linux Mint 21.2
  - RHEL 8.x
  - RHEL 9.x

<br>

* List of changes made to original software
  * removed `libz.so.1`
  * removed `libstdc++.so.6`

## Using AppImage package

AppImage file can be launched from GUI or CLI. You will need to initially use CLI to create persistent UDEV rule for your Startech adapter device.

Show supported list of Linux distributions.

```console
./Startech-NOTECONS01-USB-Crash-Cart-Adapter-XXXXXXXX-x86_64.AppImage supported
```

Show version of current AppImage build.

```console
./Startech-NOTECONS01-USB-Crash-Cart-Adapter-XXXXXXXX-x86_64.AppImage version
```

Create persistent UDEV rule on your system. Without this step, Startech software won't be able to access adapter device if you're running AppImage as a non-root user.

```console
sudo ./Startech-NOTECONS01-USB-Crash-Cart-Adapter-XXXXXXXX-x86_64.AppImage udev-install
```
