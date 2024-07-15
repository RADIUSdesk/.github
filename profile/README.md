# RADIUSdesk overview
RADIUSdesk is a system for rapid provisioning and control of the Internet in communities.<br/>
It consists of three main components
* **RADIUSdesk** - FreeRADIUS front-end.
* **MESHdesk** - Manage **Batman-adv** based Wi-Fi mesh networks in the blink of  an eye.
* **APdesk** - Manage thousands of access points with ease.

![picture alt](https://raw.githubusercontent.com/RADIUSdesk/RADIUSdesk.github.io/main/images/pr/pr5.png "RADIUSdesk Screenshot") 

# Our goals
Provide a centralised management system for your **Internet users** and **hardware** that is:
   * Easy to use.
   * 100% under your control.
   * 100% open source.

# Technology used
* The system runs on Ubuntu, although it can also run on other Linux distributions.
* We use
   * **NGINX** for the web server.
   * **MariaDB** to store the data.
   * **CakePHP** to create an API.
   * **ExtJs** to present a modern GUI that interacts with the API.
* We provide an add-on package to OpenWrt that allows you to control the hardware centrally.
   * Modular and written in **Lua**.
   * Also includes a **Luci** component.
   * Support for Wi-Fi 6 is included.
   * Works with OpenWrt 22.05.x

# Getting started
There are repositories pinned below.<br/>
Each has its own wiki page with instructions.
* **rdcore** for the installation of the central administration system.
* **openwrt-meshdesk** for compiling the OpenWrt firmware with the **MESHdesk** package.

# History
* RADIUSdesk will be 12 years old in 2024.
* We started the project in 2012 on SourceForge.
* In 2022, we are finally moved the project to Github.
* When we started, we initially used
   * Ubuntu 10.04
   * FreeRADIUS 2.x
   * ExtJS 4.0
   * CakePHP 2.x
   * OpenWrt Attitude Adjustment (12.09)
   * Single radio hardware for the mesh networks using 802.11n (Wi-Fi 4)
* Today we use
    * Ubuntu 24.04
    * FreeRADIUS 3.x
    * ExtJS 7.0
    * CakePHP 4.x
    * OpenWrt 23.05.x
    * Hardware with up to three radios using 802.11n/ac/ax (Wi-Fi 4/5/6)  

# Licensing
* All the code is published under the **GNU General Public License v3.0**.<br/>
* This means that you may make modifications and changes.

# Funding

This project also received funding through [NGI0 Entrust](https://nlnet.nl/entrust), a fund established by [NLnet](https://nlnet.nl) with financial support from the European Commission's [Next Generation Internet](https://ngi.eu) program.<br/>
Learn more at the [NLnet project page](https://nlnet.nl/project/RADIUSdesk-Multiwan).<br/>
<br/>
[<img src="https://nlnet.nl/logo/banner.png" alt="NLnet foundation logo" width="20%" />](https://nlnet.nl)<br/>
[<img src="https://nlnet.nl/image/logos/NGI0_tag.svg" alt="NGI Zero Logo" width="20%" />](https://nlnet.nl/entrust)<br/>


