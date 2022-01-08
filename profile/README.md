# RADIUSdesk overview
RADIUSdesk is a system to rapidly provide and control Internet in communities.<br/>
It consists of three main components
* **RADIUSdesk** - FreeRADIUS front-end.
* **MESHdesk** - Manage **Batman-adv** based Wi-Fi mesh networks in a snap.
* **APdesk** - Manage thousands of Access Points with ease.

![picture alt](https://raw.githubusercontent.com/RADIUSdesk/RADIUSdesk.github.io/main/images/pr/pr5.png "RADIUSdesk Screenshot") 


# Our goals
Provide a central management system for your **Internet users** and **hardware** that is:
   * Easy to use.
   * 100% under your control.
   * 100% Open Source.

# Technology used
* The system runs on Ubuntu although it can run on other Linux distros as well.
* We use
   * **NGINX** for the web server.
   * **MariaDB** to store the data.
   * **CakePHP** to create an API.
   * **ExtJs** to present a modern GUI that interacts with the API.
* We provide an add-on package to OpenWrt that allows you to centrally controll the hardware.
   * Modular and written in **Lua**.
   * Also include a **Luci** component.
   * Support for Wi-Fi 6 is included.
   * Works with OpenWrt 21.02.x

# Getting started
There are pinned repositories below.<br/>
Each one comes with their own Wiki pages containing instructions.
* **rdcore** for installing the central management system.
* **openwrt-meshdesk** for compiling OpenWrt firmware with the **MESHdesk** package.

# Licensing
All the code is released under the **GNU General Public License v3.0**.<br/>
This means you are allowed to do modifications and changes.


